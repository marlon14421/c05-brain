---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1076"
target_object: "T1012"
stix_relationship_id: "relationship--e8805949-55f7-47cd-965c-2edd4221da12"
---
# Relationship 4444: S1076 — uses → T1012

**Source object:** [[01 ATT&CK/S1076 - QUIETCANARY|S1076: QUIETCANARY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QUIETCANARY](https://attack.mitre.org/software/S1076) has the ability to retrieve information from the Registry.(Citation: Mandiant Suspected Turla Campaign February 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e8805949-55f7-47cd-965c-2edd4221da12`.
