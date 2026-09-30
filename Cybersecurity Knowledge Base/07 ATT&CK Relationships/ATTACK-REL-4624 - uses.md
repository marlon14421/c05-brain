---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0023"
target_object: "T1092"
stix_relationship_id: "relationship--167d7b11-01f3-42d5-bb8a-78306dc80243"
---
# Relationship 4624: S0023 — uses → T1092

**Source object:** [[01 ATT&CK/S0023 - CHOPSTICK|S0023: CHOPSTICK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1092 - Communication Through Removable Media|T1092: Communication Through Removable Media]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

Part of [APT28](https://attack.mitre.org/groups/G0007)'s operation involved using [CHOPSTICK](https://attack.mitre.org/software/S0023) modules to copy itself to air-gapped machines, using files written to USB sticks to transfer data and command traffic.(Citation: FireEye APT28)(Citation: ESET Sednit Part 2)(Citation: Microsoft SIR Vol 19)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--167d7b11-01f3-42d5-bb8a-78306dc80243`.
