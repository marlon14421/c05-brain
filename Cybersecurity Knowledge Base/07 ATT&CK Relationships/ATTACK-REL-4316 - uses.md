---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1043"
target_object: "T1074.001"
stix_relationship_id: "relationship--966ce7a3-4306-4003-89d8-9d6af89a0c2e"
---
# Relationship 4316: S1043 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1043 - ccf32|S1043: ccf32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ccf32](https://attack.mitre.org/software/S1043) can temporarily store files in a hidden directory on the local host.(Citation: Bitdefender FunnyDream Campaign November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--966ce7a3-4306-4003-89d8-9d6af89a0c2e`.
