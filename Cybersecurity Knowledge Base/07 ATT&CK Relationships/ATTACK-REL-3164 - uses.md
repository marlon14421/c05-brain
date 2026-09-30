---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1003"
target_object: "T1119"
stix_relationship_id: "relationship--3b7d8e64-9f14-486a-aae3-170834dac98c"
---
# Relationship 3164: G1003 — uses → T1119

**Source object:** [[01 ATT&CK/G1003 - Ember Bear|G1003: Ember Bear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ember Bear](https://attack.mitre.org/groups/G1003) engages in mass collection from compromised systems during intrusions.(Citation: Cadet Blizzard emerges as novel threat actor)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3b7d8e64-9f14-486a-aae3-170834dac98c`.
