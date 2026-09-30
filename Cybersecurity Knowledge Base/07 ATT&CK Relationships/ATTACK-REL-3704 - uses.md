---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0030"
target_object: "S0082"
stix_relationship_id: "relationship--764b5d56-83a1-4c8d-824a-2021c7fe8052"
---
# Relationship 3704: G0030 — uses → S0082

**Source object:** [[01 ATT&CK/G0030 - Lotus Blossom|G0030: Lotus Blossom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0082 - Emissary|S0082: Emissary]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lotus Blossom](https://attack.mitre.org/groups/G0030) has used [Emissary](https://attack.mitre.org/software/S0082).(Citation: Lotus Blossom Dec 2015)(Citation: Emissary Trojan Feb 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--764b5d56-83a1-4c8d-824a-2021c7fe8052`.
