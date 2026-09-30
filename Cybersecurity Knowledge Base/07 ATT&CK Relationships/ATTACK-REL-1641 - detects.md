---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0449"
target_object: "T1578.002"
stix_relationship_id: "relationship--5cc1e1a1-3cce-4282-8001-3a2c6c2af44c"
---
# Relationship 1641: DET0449 — detects → T1578.002

**Source object:** [[01 ATT&CK/DET0449 - Detection Strategy for Modify Cloud Compute Infrastructure- Create Cloud Instance|DET0449: Detection Strategy for Modify Cloud Compute Infrastructure: Create Cloud Instance]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1578.002 - Create Cloud Instance|T1578.002: Create Cloud Instance]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5cc1e1a1-3cce-4282-8001-3a2c6c2af44c`.
