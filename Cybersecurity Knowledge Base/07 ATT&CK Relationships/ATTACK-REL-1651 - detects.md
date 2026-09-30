---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0385"
target_object: "T1552.003"
stix_relationship_id: "relationship--e34c3bf9-4bb9-4afb-87f4-ba83818f7ee8"
---
# Relationship 1651: DET0385 — detects → T1552.003

**Source object:** [[01 ATT&CK/DET0385 - Detect Access and Parsing of .bash_history Files for Credential Harvesting|DET0385: Detect Access and Parsing of .bash_history Files for Credential Harvesting]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1552.003 - Shell History|T1552.003: Shell History]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e34c3bf9-4bb9-4afb-87f4-ba83818f7ee8`.
