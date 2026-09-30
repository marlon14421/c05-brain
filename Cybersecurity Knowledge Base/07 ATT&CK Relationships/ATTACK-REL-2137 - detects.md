---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0443"
target_object: "T1036.009"
stix_relationship_id: "relationship--cf6b6a0b-4dac-4fe8-92df-9b7587808512"
---
# Relationship 2137: DET0443 — detects → T1036.009

**Source object:** [[01 ATT&CK/DET0443 - Detection Strategy for Masquerading via Breaking Process Trees|DET0443: Detection Strategy for Masquerading via Breaking Process Trees]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1036.009 - Break Process Trees|T1036.009: Break Process Trees]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cf6b6a0b-4dac-4fe8-92df-9b7587808512`.
