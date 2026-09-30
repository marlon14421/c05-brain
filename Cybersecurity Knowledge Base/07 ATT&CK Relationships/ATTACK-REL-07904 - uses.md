---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "S0154"
stix_relationship_id: "relationship--b6f1f9f1-05d9-4ac6-b191-404443430b2b"
---
# Relationship 7904: G0096 — uses → S0154

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: FireEye APT41 March 2020)(Citation: Group IB APT 41 June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6f1f9f1-05d9-4ac6-b191-404443430b2b`.
