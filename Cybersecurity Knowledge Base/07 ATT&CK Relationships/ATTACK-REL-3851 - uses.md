---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0089"
target_object: "T1124"
stix_relationship_id: "relationship--f368f221-bcd5-400d-b350-83173de26423"
---
# Relationship 3851: G0089 — uses → T1124

**Source object:** [[01 ATT&CK/G0089 - The White Company|G0089: The White Company]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[The White Company](https://attack.mitre.org/groups/G0089) has checked the current date on the victim system.(Citation: Cylance Shaheen Nov 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f368f221-bcd5-400d-b350-83173de26423`.
