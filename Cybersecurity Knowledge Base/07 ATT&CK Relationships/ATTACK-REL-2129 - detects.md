---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0485"
target_object: "T1568.001"
stix_relationship_id: "relationship--0b412564-79d1-4393-988a-90fbb17e1a6f"
---
# Relationship 2129: DET0485 — detects → T1568.001

**Source object:** [[01 ATT&CK/DET0485 - Detection Strategy for Dynamic Resolution using Fast Flux DNS|DET0485: Detection Strategy for Dynamic Resolution using Fast Flux DNS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1568.001 - Fast Flux DNS|T1568.001: Fast Flux DNS]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b412564-79d1-4393-988a-90fbb17e1a6f`.
