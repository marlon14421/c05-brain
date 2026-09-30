---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0583"
target_object: "T1136"
stix_relationship_id: "relationship--bd9b60eb-dc7a-4806-b882-040b17e4f5b4"
---
# Relationship 2055: DET0583 — detects → T1136

**Source object:** [[01 ATT&CK/DET0583 - Detection Strategy for T1136 - Create Account across platforms|DET0583: Detection Strategy for T1136 - Create Account across platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1136 - Create Account|T1136: Create Account]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd9b60eb-dc7a-4806-b882-040b17e4f5b4`.
