---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1172"
target_object: "T1106"
stix_relationship_id: "relationship--fd492de4-85fc-42a3-a499-d49d55c3b252"
---
# Relationship 7116: S1172 — uses → T1106

**Source object:** [[01 ATT&CK/S1172 - OilBooster|S1172: OilBooster]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilBooster](https://attack.mitre.org/software/S1172) has used the `ShowWindow` and `CreateProcessW` APIs.(Citation: ESET OilRig Downloaders DEC 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd492de4-85fc-42a3-a499-d49d55c3b252`.
