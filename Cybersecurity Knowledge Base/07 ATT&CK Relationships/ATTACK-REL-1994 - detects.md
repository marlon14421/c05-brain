---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0321"
target_object: "T1564.006"
stix_relationship_id: "relationship--3ef5c5df-8e91-49c0-bdf8-e2d826c5e7b3"
---
# Relationship 1994: DET0321 — detects → T1564.006

**Source object:** [[01 ATT&CK/DET0321 - Detection Strategy for Hidden Virtual Instance Execution|DET0321: Detection Strategy for Hidden Virtual Instance Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1564.006 - Run Virtual Instance|T1564.006: Run Virtual Instance]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ef5c5df-8e91-49c0-bdf8-e2d826c5e7b3`.
