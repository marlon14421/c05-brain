---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0127"
target_object: "T1568.002"
stix_relationship_id: "relationship--93656c66-acfc-43b4-af66-bf328256b7b8"
---
# Relationship 3021: G0127 — uses → T1568.002

**Source object:** [[01 ATT&CK/G0127 - TA551|G0127: TA551]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568.002 - Domain Generation Algorithms|T1568.002: Domain Generation Algorithms]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA551](https://attack.mitre.org/groups/G0127) has used a DGA to generate URLs from executed macros.(Citation: Unit 42 TA551 Jan 2021)(Citation: Secureworks GOLD CABIN)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93656c66-acfc-43b4-af66-bf328256b7b8`.
