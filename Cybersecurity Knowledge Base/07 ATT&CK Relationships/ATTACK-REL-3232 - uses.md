---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1099"
target_object: "T1012"
stix_relationship_id: "relationship--c4179f06-f1e8-432c-81db-c88b3a37f0bc"
---
# Relationship 3232: S1099 — uses → T1012

**Source object:** [[01 ATT&CK/S1099 - Samurai|S1099: Samurai]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Samurai](https://attack.mitre.org/software/S1099) can query `SOFTWARE\Microsoft\.NETFramework\policy\v2.0` for discovery.(Citation: Kaspersky ToddyCat June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4179f06-f1e8-432c-81db-c88b3a37f0bc`.
