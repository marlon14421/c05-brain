---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0028"
target_object: "T1685"
stix_relationship_id: "relationship--273e10a7-c598-4e06-be21-a8ec7537eeb6"
---
# Relationship 4102: C0028 — uses → T1685

**Source object:** [[01 ATT&CK/C0028 - 2015 Ukraine Electric Power Attack|C0028: 2015 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [2015 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0028), [Sandworm Team](https://attack.mitre.org/groups/G0034) modified in-registry internet settings to lower internet security. (Citation: Booz Allen Hamilton)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--273e10a7-c598-4e06-be21-a8ec7537eeb6`.
