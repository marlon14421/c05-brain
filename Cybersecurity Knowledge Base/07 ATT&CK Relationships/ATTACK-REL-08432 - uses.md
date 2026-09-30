---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1014"
target_object: "S0013"
stix_relationship_id: "relationship--71485f5d-f685-403d-a0da-72acbae0f79e"
---
# Relationship 8432: G1014 — uses → S0013

**Source object:** [[01 ATT&CK/G1014 - LuminousMoth|G1014: LuminousMoth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71485f5d-f685-403d-a0da-72acbae0f79e`.
