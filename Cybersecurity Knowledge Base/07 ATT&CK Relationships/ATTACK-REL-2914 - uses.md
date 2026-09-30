---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1009"
target_object: "S1034"
stix_relationship_id: "relationship--610421e6-aa2f-4756-817b-57458e4959ad"
---
# Relationship 2914: G1009 — uses → S1034

**Source object:** [[01 ATT&CK/G1009 - Moses Staff|G1009: Moses Staff]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1034 - StrifeWater|S1034: StrifeWater]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Cybereason StrifeWater Feb 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--610421e6-aa2f-4756-817b-57458e4959ad`.
