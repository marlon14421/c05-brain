---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0333"
target_object: "T1053.002"
stix_relationship_id: "relationship--4928c2f8-a102-4a33-9543-8df8ecb8e806"
---
# Relationship 1956: DET0333 — detects → T1053.002

**Source object:** [[01 ATT&CK/DET0333 - Cross-Platform Detection of Scheduled Task-Job Abuse via `at` Utility|DET0333: Cross-Platform Detection of Scheduled Task/Job Abuse via `at` Utility]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1053.002 - At|T1053.002: At]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4928c2f8-a102-4a33-9543-8df8ecb8e806`.
