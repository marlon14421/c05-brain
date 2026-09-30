---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0067"
target_object: "T1564.011"
stix_relationship_id: "relationship--3e72be77-01a0-4fd7-b404-6e8b7b090034"
---
# Relationship 1539: DET0067 — detects → T1564.011

**Source object:** [[01 ATT&CK/DET0067 - Detection Strategy for Ignore Process Interrupts|DET0067: Detection Strategy for Ignore Process Interrupts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1564.011 - Ignore Process Interrupts|T1564.011: Ignore Process Interrupts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e72be77-01a0-4fd7-b404-6e8b7b090034`.
