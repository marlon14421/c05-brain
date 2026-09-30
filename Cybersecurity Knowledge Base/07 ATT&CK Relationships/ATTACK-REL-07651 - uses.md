---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0631"
target_object: "T1112"
stix_relationship_id: "relationship--9fde7504-bd24-46f5-88d7-4afcb8d37f4a"
---
# Relationship 7651: S0631 — uses → T1112

**Source object:** [[01 ATT&CK/S0631 - Chaes|S0631: Chaes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chaes](https://attack.mitre.org/software/S0631) can modify Registry values to stored information and establish persistence.(Citation: Cybereason Chaes Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9fde7504-bd24-46f5-88d7-4afcb8d37f4a`.
