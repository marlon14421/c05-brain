---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1037"
target_object: "S1145"
stix_relationship_id: "relationship--01a4bef1-5445-4e46-90db-fd4335462be1"
---
# Relationship 4499: G1037 — uses → S1145

**Source object:** [[01 ATT&CK/G1037 - TA577|G1037: TA577]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1145 - Pikabot|S1145: Pikabot]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Latrodectus APR 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--01a4bef1-5445-4e46-90db-fd4335462be1`.
