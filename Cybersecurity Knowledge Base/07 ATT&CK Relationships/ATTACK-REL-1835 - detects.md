---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0074"
target_object: "T1550.004"
stix_relationship_id: "relationship--c954ce9b-4575-438d-8298-ed4294aed9b7"
---
# Relationship 1835: DET0074 — detects → T1550.004

**Source object:** [[01 ATT&CK/DET0074 - Detect Use of Stolen Web Session Cookies Across Platforms|DET0074: Detect Use of Stolen Web Session Cookies Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1550.004 - Web Session Cookie|T1550.004: Web Session Cookie]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c954ce9b-4575-438d-8298-ed4294aed9b7`.
