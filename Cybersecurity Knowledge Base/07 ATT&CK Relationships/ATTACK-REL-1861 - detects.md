---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0395"
target_object: "T1548.004"
stix_relationship_id: "relationship--2d0b8891-2763-4370-bb63-6f41dfcdd965"
---
# Relationship 1861: DET0395 — detects → T1548.004

**Source object:** [[01 ATT&CK/DET0395 - macOS AuthorizationExecuteWithPrivileges Elevation Prompt Detection|DET0395: macOS AuthorizationExecuteWithPrivileges Elevation Prompt Detection]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1548.004 - Elevated Execution with Prompt|T1548.004: Elevated Execution with Prompt]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d0b8891-2763-4370-bb63-6f41dfcdd965`.
