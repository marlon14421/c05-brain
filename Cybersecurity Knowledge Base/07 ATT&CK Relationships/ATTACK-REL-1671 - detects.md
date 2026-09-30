---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0806"
target_object: "T1591.001"
stix_relationship_id: "relationship--673aa35e-a5b3-4921-b950-135c2d0d7edb"
---
# Relationship 1671: DET0806 — detects → T1591.001

**Source object:** [[01 ATT&CK/DET0806 - Detection of Determine Physical Locations|DET0806: Detection of Determine Physical Locations]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1591.001 - Determine Physical Locations|T1591.001: Determine Physical Locations]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--673aa35e-a5b3-4921-b950-135c2d0d7edb`.
