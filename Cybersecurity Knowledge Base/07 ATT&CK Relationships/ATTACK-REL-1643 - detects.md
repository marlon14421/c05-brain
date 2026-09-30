---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0217"
target_object: "T1055.011"
stix_relationship_id: "relationship--606a9fa1-9738-4372-b2c7-d0bad6c84854"
---
# Relationship 1643: DET0217 — detects → T1055.011

**Source object:** [[01 ATT&CK/DET0217 - Detection Strategy for Extra Window Memory (EWM) Injection on Windows|DET0217: Detection Strategy for Extra Window Memory (EWM) Injection on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1055.011 - Extra Window Memory Injection|T1055.011: Extra Window Memory Injection]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--606a9fa1-9738-4372-b2c7-d0bad6c84854`.
