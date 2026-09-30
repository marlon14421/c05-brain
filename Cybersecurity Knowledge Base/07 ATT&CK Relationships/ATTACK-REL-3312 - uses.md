---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "S0002"
stix_relationship_id: "relationship--dfd6892f-82a4-4db4-a132-3d6f221e55f4"
---
# Relationship 3312: G0035 — uses → S0002

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Secureworks IRON LIBERTY July 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dfd6892f-82a4-4db4-a132-3d6f221e55f4`.
