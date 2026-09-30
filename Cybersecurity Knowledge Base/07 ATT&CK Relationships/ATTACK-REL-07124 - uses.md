---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0688"
target_object: "T1484.001"
stix_relationship_id: "relationship--f9b7c51c-fcb1-4cf7-b19d-ecd92291326c"
---
# Relationship 7124: S0688 — uses → T1484.001

**Source object:** [[01 ATT&CK/S0688 - Meteor|S0688: Meteor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1484.001 - Group Policy Modification|T1484.001: Group Policy Modification]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Meteor](https://attack.mitre.org/software/S0688) can use group policy to push a scheduled task from the AD to all network machines.(Citation: Check Point Meteor Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f9b7c51c-fcb1-4cf7-b19d-ecd92291326c`.
