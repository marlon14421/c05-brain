---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0394"
target_object: "T1505.003"
stix_relationship_id: "relationship--6b31d2da-bc19-4d4e-9da4-b61688d0bd39"
---
# Relationship 2127: DET0394 — detects → T1505.003

**Source object:** [[01 ATT&CK/DET0394 - Web Shell Detection via Server Behavior and File Execution Chains|DET0394: Web Shell Detection via Server Behavior and File Execution Chains]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b31d2da-bc19-4d4e-9da4-b61688d0bd39`.
