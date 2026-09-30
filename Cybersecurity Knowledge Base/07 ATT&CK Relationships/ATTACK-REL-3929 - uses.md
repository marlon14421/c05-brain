---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0606"
target_object: "T1106"
stix_relationship_id: "relationship--b2852e21-c31a-482a-85fd-00d0990ee8ea"
---
# Relationship 3929: S0606 — uses → T1106

**Source object:** [[01 ATT&CK/S0606 - Bad Rabbit|S0606: Bad Rabbit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bad Rabbit](https://attack.mitre.org/software/S0606) has used various Windows API calls.(Citation: ESET Bad Rabbit)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b2852e21-c31a-482a-85fd-00d0990ee8ea`.
