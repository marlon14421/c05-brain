---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0523"
target_object: "T1553.006"
stix_relationship_id: "relationship--cfb6fe1a-05c5-4b7a-86c7-4ae65c9f37a1"
---
# Relationship 1662: DET0523 — detects → T1553.006

**Source object:** [[01 ATT&CK/DET0523 - Detect Code Signing Policy Modification (Windows & macOS)|DET0523: Detect Code Signing Policy Modification (Windows & macOS)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1553.006 - Code Signing Policy Modification|T1553.006: Code Signing Policy Modification]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfb6fe1a-05c5-4b7a-86c7-4ae65c9f37a1`.
