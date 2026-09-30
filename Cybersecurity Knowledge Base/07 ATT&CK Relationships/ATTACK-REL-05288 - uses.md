---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0688"
target_object: "T1070.004"
stix_relationship_id: "relationship--ee8711e0-dd0e-4730-9b85-bd55fb6d590e"
---
# Relationship 5288: S0688 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0688 - Meteor|S0688: Meteor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Meteor](https://attack.mitre.org/software/S0688) will delete the folder containing malicious scripts if it detects the hostname as `PIS-APP`, `PIS-MOB`, `WSUSPROXY`, or `PIS-DB`.(Citation: Check Point Meteor Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ee8711e0-dd0e-4730-9b85-bd55fb6d590e`.
