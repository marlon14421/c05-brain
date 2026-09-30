---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0209"
target_object: "T1012"
stix_relationship_id: "relationship--e4fec267-da7b-4c33-bf87-d3b2fc2b0513"
---
# Relationship 2046: DET0209 — detects → T1012

**Source object:** [[01 ATT&CK/DET0209 - Detection of Registry Query for Environmental Discovery|DET0209: Detection of Registry Query for Environmental Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e4fec267-da7b-4c33-bf87-d3b2fc2b0513`.
