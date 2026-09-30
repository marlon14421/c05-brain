---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0219"
target_object: "T1611"
stix_relationship_id: "relationship--a7131e1e-1898-403a-b431-099e7c62393c"
---
# Relationship 2112: DET0219 — detects → T1611

**Source object:** [[01 ATT&CK/DET0219 - Detection Strategy for Escape to Host|DET0219: Detection Strategy for Escape to Host]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1611 - Escape to Host|T1611: Escape to Host]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a7131e1e-1898-403a-b431-099e7c62393c`.
