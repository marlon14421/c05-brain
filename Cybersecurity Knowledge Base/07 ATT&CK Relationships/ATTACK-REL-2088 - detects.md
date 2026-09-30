---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0916"
target_object: "T1683"
stix_relationship_id: "relationship--68b1bd9b-5d0c-426f-b510-e323ab629552"
---
# Relationship 2088: DET0916 — detects → T1683

**Source object:** [[01 ATT&CK/DET0916 - Detection of Generate Content|DET0916: Detection of Generate Content]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1683 - Generate Content|T1683: Generate Content]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68b1bd9b-5d0c-426f-b510-e323ab629552`.
