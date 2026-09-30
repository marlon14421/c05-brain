---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0562"
target_object: "T1480"
stix_relationship_id: "relationship--d1b82c9a-003e-4eb2-b34d-d2b2dbbebe19"
---
# Relationship 1732: DET0562 — detects → T1480

**Source object:** [[01 ATT&CK/DET0562 - Multi-Platform Execution Guardrails Environmental Validation Detection Strategy|DET0562: Multi-Platform Execution Guardrails Environmental Validation Detection Strategy]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d1b82c9a-003e-4eb2-b34d-d2b2dbbebe19`.
