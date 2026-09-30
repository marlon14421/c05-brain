---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0075"
target_object: "T1053.005"
stix_relationship_id: "relationship--7121357f-cc91-4e6b-a2a6-d8bb51bf4a01"
---
# Relationship 2949: G0075 — uses → T1053.005

**Source object:** [[01 ATT&CK/G0075 - Rancor|G0075: Rancor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Rancor](https://attack.mitre.org/groups/G0075) launched a scheduled task to gain persistence using the schtasks /create /sc command.(Citation: Rancor Unit42 June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7121357f-cc91-4e6b-a2a6-d8bb51bf4a01`.
