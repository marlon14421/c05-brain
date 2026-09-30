---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9032"
target_object: "T1106"
stix_relationship_id: "relationship--77811f16-814c-45e5-b922-1b2be86239d3"
---
# Relationship 4283: S9032 — uses → T1106

**Source object:** [[01 ATT&CK/S9032 - MuddyViper|S9032: MuddyViper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MuddyViper](https://attack.mitre.org/software/S9032) has the ability to relaunch itself using the `CreateProcessW` API.(Citation: ESET_MuddyWater_Dec2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77811f16-814c-45e5-b922-1b2be86239d3`.
