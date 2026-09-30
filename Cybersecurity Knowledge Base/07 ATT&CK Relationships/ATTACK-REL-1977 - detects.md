---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0557"
target_object: "T1546.010"
stix_relationship_id: "relationship--c1e7f701-1a6e-4f87-89fb-f929a0034b88"
---
# Relationship 1977: DET0557 — detects → T1546.010

**Source object:** [[01 ATT&CK/DET0557 - Detection Strategy for Event Triggered Execution- AppInit DLLs (Windows)|DET0557: Detection Strategy for Event Triggered Execution: AppInit DLLs (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.010 - AppInit DLLs|T1546.010: AppInit DLLs]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1e7f701-1a6e-4f87-89fb-f929a0034b88`.
