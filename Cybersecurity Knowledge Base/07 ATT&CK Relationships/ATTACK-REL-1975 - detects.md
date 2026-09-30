---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0409"
target_object: "T1550.002"
stix_relationship_id: "relationship--fa64735f-0ea6-482b-859a-5cb4b9f6f95b"
---
# Relationship 1975: DET0409 — detects → T1550.002

**Source object:** [[01 ATT&CK/DET0409 - Detection Strategy for T1550.002 - Pass the Hash (Windows)|DET0409: Detection Strategy for T1550.002 - Pass the Hash (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1550.002 - Pass the Hash|T1550.002: Pass the Hash]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa64735f-0ea6-482b-859a-5cb4b9f6f95b`.
