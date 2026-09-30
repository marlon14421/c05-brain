---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1032"
target_object: "T1036.005"
stix_relationship_id: "relationship--9defa430-9c4c-4dde-b952-d75394c8fd5e"
---
# Relationship 4329: G1032 — uses → T1036.005

**Source object:** [[01 ATT&CK/G1032 - INC Ransom|G1032: INC Ransom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[INC Ransom](https://attack.mitre.org/groups/G1032) has named a [PsExec](https://attack.mitre.org/software/S0029) executable winupd to mimic a legitimate Windows update file.(Citation: Huntress INC Ransom Group August 2023)(Citation: SOCRadar INC Ransom January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9defa430-9c4c-4dde-b952-d75394c8fd5e`.
