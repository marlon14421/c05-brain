---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0479"
target_object: "T1574.012"
stix_relationship_id: "relationship--d6cbd80f-a221-4c61-b859-c54576b15b0e"
---
# Relationship 1677: DET0479 — detects → T1574.012

**Source object:** [[01 ATT&CK/DET0479 - Detection Strategy for Hijack Execution Flow using the Windows COR_PROFILER|DET0479: Detection Strategy for Hijack Execution Flow using the Windows COR_PROFILER.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574.012 - COR_PROFILER|T1574.012: COR_PROFILER]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6cbd80f-a221-4c61-b859-c54576b15b0e`.
