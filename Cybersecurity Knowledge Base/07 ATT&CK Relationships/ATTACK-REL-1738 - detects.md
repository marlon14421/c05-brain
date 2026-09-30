---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0511"
target_object: "T1025"
stix_relationship_id: "relationship--b3d51de7-1b65-4b89-9768-31c96a731a4d"
---
# Relationship 1738: DET0511 — detects → T1025

**Source object:** [[01 ATT&CK/DET0511 - Detection of Data Access and Collection from Removable Media|DET0511: Detection of Data Access and Collection from Removable Media]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1025 - Data from Removable Media|T1025: Data from Removable Media]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b3d51de7-1b65-4b89-9768-31c96a731a4d`.
