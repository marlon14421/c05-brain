---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1017"
target_object: "T1087.001"
stix_relationship_id: "relationship--648a19d0-2728-4be8-ac62-4bf08a4265a6"
---
# Relationship 3020: G1017 — uses → T1087.001

**Source object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Volt Typhoon](https://attack.mitre.org/groups/G1017) has executed `net user` and `quser` to enumerate local account information.(Citation: CISA AA24-038A PRC Critical Infrastructure February 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--648a19d0-2728-4be8-ac62-4bf08a4265a6`.
