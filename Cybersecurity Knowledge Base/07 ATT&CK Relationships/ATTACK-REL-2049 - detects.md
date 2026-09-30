---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0281"
target_object: "T1027.015"
stix_relationship_id: "relationship--432c35d1-b40e-401c-8c75-601a5cf0f86e"
---
# Relationship 2049: DET0281 — detects → T1027.015

**Source object:** [[01 ATT&CK/DET0281 - Detection Strategy for Compressed Payload Creation and Execution|DET0281: Detection Strategy for Compressed Payload Creation and Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--432c35d1-b40e-401c-8c75-601a5cf0f86e`.
