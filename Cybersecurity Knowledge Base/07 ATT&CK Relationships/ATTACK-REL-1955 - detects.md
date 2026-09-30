---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0084"
target_object: "T1578.003"
stix_relationship_id: "relationship--38973fa3-5d24-4da8-ba12-26c45acf0439"
---
# Relationship 1955: DET0084 — detects → T1578.003

**Source object:** [[01 ATT&CK/DET0084 - Detection Strategy for Modify Cloud Compute Infrastructure- Delete Cloud Instance|DET0084: Detection Strategy for Modify Cloud Compute Infrastructure: Delete Cloud Instance]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1578.003 - Delete Cloud Instance|T1578.003: Delete Cloud Instance]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38973fa3-5d24-4da8-ba12-26c45acf0439`.
