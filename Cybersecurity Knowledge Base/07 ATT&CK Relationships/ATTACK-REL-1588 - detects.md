---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0132"
target_object: "T1480.002"
stix_relationship_id: "relationship--fe03f09f-ee1e-40ce-a413-a06b023e80f6"
---
# Relationship 1588: DET0132 — detects → T1480.002

**Source object:** [[01 ATT&CK/DET0132 - Detection of Mutex-Based Execution Guardrails Across Platforms|DET0132: Detection of Mutex-Based Execution Guardrails Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe03f09f-ee1e-40ce-a413-a06b023e80f6`.
