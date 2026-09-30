---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0056"
target_object: "S0491"
stix_relationship_id: "relationship--bc4252e5-6a2a-443e-9a31-16d86f4f069b"
---
# Relationship 7247: G0056 — uses → S0491

**Source object:** [[01 ATT&CK/G0056 - PROMETHIUM|G0056: PROMETHIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0491 - StrongPity|S0491: StrongPity]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Bitdefender StrongPity June 2020)(Citation: Talos Promethium June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc4252e5-6a2a-443e-9a31-16d86f4f069b`.
