---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0183"
target_object: "T1570"
stix_relationship_id: "relationship--f66b9063-a4c3-4f41-8fb3-4a7ea1eeb34c"
---
# Relationship 2050: DET0183 — detects → T1570

**Source object:** [[01 ATT&CK/DET0183 - Detection Strategy for Lateral Tool Transfer across OS platforms|DET0183: Detection Strategy for Lateral Tool Transfer across OS platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f66b9063-a4c3-4f41-8fb3-4a7ea1eeb34c`.
