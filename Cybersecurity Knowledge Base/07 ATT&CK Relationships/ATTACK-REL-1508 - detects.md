---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0026"
target_object: "T1547.012"
stix_relationship_id: "relationship--1ac36840-525f-4361-86dc-3d6567a18b0a"
---
# Relationship 1508: DET0026 — detects → T1547.012

**Source object:** [[01 ATT&CK/DET0026 - Windows Detection Strategy for T1547.012 - Print Processor DLL Persistence|DET0026: Windows Detection Strategy for T1547.012 - Print Processor DLL Persistence]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.012 - Print Processors|T1547.012: Print Processors]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ac36840-525f-4361-86dc-3d6567a18b0a`.
