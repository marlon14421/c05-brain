---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0017"
target_object: "S0013"
stix_relationship_id: "relationship--ee2739de-6829-4c73-b72b-91ba4b9fac5c"
---
# Relationship 4352: G0017 — uses → S0013

**Source object:** [[01 ATT&CK/G0017 - DragonOK|G0017: DragonOK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: New DragonOK)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ee2739de-6829-4c73-b72b-91ba4b9fac5c`.
