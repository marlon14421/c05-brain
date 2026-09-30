---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1005"
target_object: "S1024"
stix_relationship_id: "relationship--a3a4fbbe-3559-4333-8285-732a3dfa0460"
---
# Relationship 3289: G1005 — uses → S1024

**Source object:** [[01 ATT&CK/G1005 - POLONIUM|G1005: POLONIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1024 - CreepySnail|S1024: CreepySnail]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Microsoft POLONIUM June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3a4fbbe-3559-4333-8285-732a3dfa0460`.
