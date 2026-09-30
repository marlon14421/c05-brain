---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0152"
target_object: "T1574.004"
stix_relationship_id: "relationship--89ecadf2-0a07-44d5-9209-6215eb4fab32"
---
# Relationship 1941: DET0152 — detects → T1574.004

**Source object:** [[01 ATT&CK/DET0152 - Detection Strategy for Hijack Execution Flow- Dylib Hijacking|DET0152: Detection Strategy for Hijack Execution Flow: Dylib Hijacking]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574.004 - Dylib Hijacking|T1574.004: Dylib Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--89ecadf2-0a07-44d5-9209-6215eb4fab32`.
