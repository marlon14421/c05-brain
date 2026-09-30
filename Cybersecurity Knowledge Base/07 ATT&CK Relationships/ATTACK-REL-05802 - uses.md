---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1053"
target_object: "T1489"
stix_relationship_id: "relationship--b56db835-3b80-49e8-964d-0c1c52d182fe"
---
# Relationship 5802: S1053 — uses → T1489

**Source object:** [[01 ATT&CK/S1053 - AvosLocker|S1053: AvosLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AvosLocker](https://attack.mitre.org/software/S1053) has terminated specific processes before encryption.(Citation: Malwarebytes AvosLocker Jul 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b56db835-3b80-49e8-964d-0c1c52d182fe`.
