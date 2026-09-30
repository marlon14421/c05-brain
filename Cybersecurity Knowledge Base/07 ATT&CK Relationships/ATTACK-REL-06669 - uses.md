---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1031"
target_object: "T1204.002"
stix_relationship_id: "relationship--80f3d913-d317-4531-9fb5-293f023f9b11"
---
# Relationship 6669: G1031 — uses → T1204.002

**Source object:** [[01 ATT&CK/G1031 - Saint Bear|G1031: Saint Bear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Saint Bear](https://attack.mitre.org/groups/G1031) relies on user interaction and execution of malicious attachments and similar for initial execution on victim systems.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80f3d913-d317-4531-9fb5-293f023f9b11`.
