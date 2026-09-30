---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0900"
target_object: "T1687"
stix_relationship_id: "relationship--1a900a55-e489-4cc5-a1c6-ded0d0daae6a"
---
# Relationship 1549: DET0900 — detects → T1687

**Source object:** [[01 ATT&CK/DET0900 - Detection of Defense Impairment|DET0900: Detection of Defense Impairment]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1687 - Exploitation for Defense Impairment|T1687: Exploitation for Defense Impairment]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a900a55-e489-4cc5-a1c6-ded0d0daae6a`.
