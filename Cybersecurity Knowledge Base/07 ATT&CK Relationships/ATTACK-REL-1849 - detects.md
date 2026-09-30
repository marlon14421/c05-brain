---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0337"
target_object: "T1578.004"
stix_relationship_id: "relationship--e4b4bdd3-07b3-4d99-b054-330260bfec0a"
---
# Relationship 1849: DET0337 — detects → T1578.004

**Source object:** [[01 ATT&CK/DET0337 - Detection Strategy for Modify Cloud Compute Infrastructure- Revert Cloud Instance|DET0337: Detection Strategy for Modify Cloud Compute Infrastructure: Revert Cloud Instance]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1578.004 - Revert Cloud Instance|T1578.004: Revert Cloud Instance]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e4b4bdd3-07b3-4d99-b054-330260bfec0a`.
