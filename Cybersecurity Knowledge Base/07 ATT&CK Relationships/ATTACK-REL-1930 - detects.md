---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0003"
target_object: "T1136.002"
stix_relationship_id: "relationship--140e6844-f9bb-4e31-bb57-370d1fd830f3"
---
# Relationship 1930: DET0003 — detects → T1136.002

**Source object:** [[01 ATT&CK/DET0003 - T1136.002 Detection Strategy - Domain Account Creation Across Platforms|DET0003: T1136.002 Detection Strategy - Domain Account Creation Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1136.002 - Domain Account|T1136.002: Domain Account]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--140e6844-f9bb-4e31-bb57-370d1fd830f3`.
