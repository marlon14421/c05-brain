---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9032"
target_object: "T1053.005"
stix_relationship_id: "relationship--5c962e5a-d3fc-48e4-b8a4-24e3172a9ce0"
---
# Relationship 5847: S9032 — uses → T1053.005

**Source object:** [[01 ATT&CK/S9032 - MuddyViper|S9032: MuddyViper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MuddyViper](https://attack.mitre.org/software/S9032) has the ability to establish persistence by creating a scheduled task named ManageOnDriveUpdater to launch itself during system startup.(Citation: ESET_MuddyWater_Dec2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c962e5a-d3fc-48e4-b8a4-24e3172a9ce0`.
