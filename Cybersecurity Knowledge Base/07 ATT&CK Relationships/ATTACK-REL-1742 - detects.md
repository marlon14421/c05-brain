---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0324"
target_object: "T1027.014"
stix_relationship_id: "relationship--471e5702-2a73-4c6d-9ed8-78b037941b6f"
---
# Relationship 1742: DET0324 — detects → T1027.014

**Source object:** [[01 ATT&CK/DET0324 - Detection Strategy for Polymorphic Code Mutation and Execution|DET0324: Detection Strategy for Polymorphic Code Mutation and Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.014 - Polymorphic Code|T1027.014: Polymorphic Code]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--471e5702-2a73-4c6d-9ed8-78b037941b6f`.
