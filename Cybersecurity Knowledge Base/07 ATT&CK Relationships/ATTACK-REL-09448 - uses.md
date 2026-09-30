---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1550.002"
stix_relationship_id: "relationship--80e06d13-4c96-464c-9b9f-d0cb2b5fac18"
---
# Relationship 9448: G0094 — uses → T1550.002

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1550.002 - Pass the Hash|T1550.002: Pass the Hash]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used pass the hash for authentication to remote access software used in C2.(Citation: CISA AA20-301A Kimsuky)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80e06d13-4c96-464c-9b9f-d0cb2b5fac18`.
