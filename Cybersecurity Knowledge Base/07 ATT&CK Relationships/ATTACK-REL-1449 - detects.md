---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0290"
target_object: "T1053.003"
stix_relationship_id: "relationship--633a820e-8988-410d-a7ff-40b24f381d74"
---
# Relationship 1449: DET0290 — detects → T1053.003

**Source object:** [[01 ATT&CK/DET0290 - Cross-Platform Detection of Cron Job Abuse for Persistence and Execution|DET0290: Cross-Platform Detection of Cron Job Abuse for Persistence and Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1053.003 - Cron|T1053.003: Cron]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--633a820e-8988-410d-a7ff-40b24f381d74`.
