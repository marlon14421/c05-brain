---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0365"
target_object: "T1547.001"
stix_relationship_id: "relationship--78cd373e-443f-46e5-bde8-b05b15ca3d1e"
---
# Relationship 1518: DET0365 — detects → T1547.001

**Source object:** [[01 ATT&CK/DET0365 - Detect Registry and Startup Folder Persistence (Windows)|DET0365: Detect Registry and Startup Folder Persistence (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--78cd373e-443f-46e5-bde8-b05b15ca3d1e`.
