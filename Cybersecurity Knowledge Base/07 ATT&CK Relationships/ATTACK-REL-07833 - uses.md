---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0688"
target_object: "T1106"
stix_relationship_id: "relationship--717cce1c-bbb9-4735-80d0-3d13ea56f248"
---
# Relationship 7833: S0688 — uses → T1106

**Source object:** [[01 ATT&CK/S0688 - Meteor|S0688: Meteor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Meteor](https://attack.mitre.org/software/S0688) can use `WinAPI` to remove a victim machine from an Active Directory domain.(Citation: Check Point Meteor Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--717cce1c-bbb9-4735-80d0-3d13ea56f248`.
