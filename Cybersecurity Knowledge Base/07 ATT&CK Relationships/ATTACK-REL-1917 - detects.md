---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0352"
target_object: "T1550.003"
stix_relationship_id: "relationship--8c7004e4-8b41-436a-91e5-6b026eeaf062"
---
# Relationship 1917: DET0352 — detects → T1550.003

**Source object:** [[01 ATT&CK/DET0352 - Detection Strategy for T1550.003 - Pass the Ticket (Windows)|DET0352: Detection Strategy for T1550.003 - Pass the Ticket (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1550.003 - Pass the Ticket|T1550.003: Pass the Ticket]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c7004e4-8b41-436a-91e5-6b026eeaf062`.
