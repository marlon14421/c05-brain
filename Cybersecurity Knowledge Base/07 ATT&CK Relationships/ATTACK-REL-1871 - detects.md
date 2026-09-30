---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0884"
target_object: "T1650"
stix_relationship_id: "relationship--2826f7b0-cbbb-4c90-a5c0-bd78aa8e1078"
---
# Relationship 1871: DET0884 — detects → T1650

**Source object:** [[01 ATT&CK/DET0884 - Detection of Acquire Access|DET0884: Detection of Acquire Access]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1650 - Acquire Access|T1650: Acquire Access]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2826f7b0-cbbb-4c90-a5c0-bd78aa8e1078`.
