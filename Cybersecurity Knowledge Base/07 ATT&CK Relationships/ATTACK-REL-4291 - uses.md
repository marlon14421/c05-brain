---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0385"
target_object: "T1106"
stix_relationship_id: "relationship--48879c97-651c-4426-9093-bd8c4939fc19"
---
# Relationship 4291: S0385 — uses → T1106

**Source object:** [[01 ATT&CK/S0385 - njRAT|S0385: njRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[njRAT](https://attack.mitre.org/software/S0385) has used the ShellExecute() function within a script.(Citation: Trend Micro njRAT 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48879c97-651c-4426-9093-bd8c4939fc19`.
