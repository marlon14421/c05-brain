---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0227"
target_object: "T1571"
stix_relationship_id: "relationship--db753357-bf72-4dfc-ad38-701dab07e7fa"
---
# Relationship 1959: DET0227 — detects → T1571

**Source object:** [[01 ATT&CK/DET0227 - Detection Strategy for Non-Standard Ports|DET0227: Detection Strategy for Non-Standard Ports]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--db753357-bf72-4dfc-ad38-701dab07e7fa`.
