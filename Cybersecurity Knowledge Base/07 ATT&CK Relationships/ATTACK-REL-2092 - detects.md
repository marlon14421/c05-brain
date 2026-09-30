---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0164"
target_object: "T1036.011"
stix_relationship_id: "relationship--c8ad2b36-a6ae-4d7b-bbe9-de8bddd3fec6"
---
# Relationship 2092: DET0164 — detects → T1036.011

**Source object:** [[01 ATT&CK/DET0164 - Detection Strategy for Overwritten Process Arguments Masquerading|DET0164: Detection Strategy for Overwritten Process Arguments Masquerading]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1036.011 - Overwrite Process Arguments|T1036.011: Overwrite Process Arguments]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8ad2b36-a6ae-4d7b-bbe9-de8bddd3fec6`.
