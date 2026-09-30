---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1053"
target_object: "T1564.003"
stix_relationship_id: "relationship--b1aab9dc-267d-4208-b1bc-14396d7e0d8d"
---
# Relationship 4879: S1053 — uses → T1564.003

**Source object:** [[01 ATT&CK/S1053 - AvosLocker|S1053: AvosLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AvosLocker](https://attack.mitre.org/software/S1053) has hidden its console window by using the `ShowWindow` API function.(Citation: Malwarebytes AvosLocker Jul 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1aab9dc-267d-4208-b1bc-14396d7e0d8d`.
