---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0020"
target_object: "T1546.004"
stix_relationship_id: "relationship--666b59c9-ba59-4f22-b4d3-5186a624bae7"
---
# Relationship 2120: DET0020 — detects → T1546.004

**Source object:** [[01 ATT&CK/DET0020 - Detect Shell Configuration Modification for Persistence via Event-Triggered Execution|DET0020: Detect Shell Configuration Modification for Persistence via Event-Triggered Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.004 - Unix Shell Configuration Modification|T1546.004: Unix Shell Configuration Modification]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--666b59c9-ba59-4f22-b4d3-5186a624bae7`.
