---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1019"
target_object: "S1088"
stix_relationship_id: "relationship--c74c6674-047a-401a-8a70-0d96d7cf243a"
---
# Relationship 3068: G1019 — uses → S1088

**Source object:** [[01 ATT&CK/G1019 - MoustachedBouncer|G1019: MoustachedBouncer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1088 - Disco|S1088: Disco]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: MoustachedBouncer ESET August 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c74c6674-047a-401a-8a70-0d96d7cf243a`.
