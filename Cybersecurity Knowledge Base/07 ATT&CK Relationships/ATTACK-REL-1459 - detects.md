---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0179"
target_object: "T1069"
stix_relationship_id: "relationship--35e5628c-ccc8-49c4-87db-2e683920288b"
---
# Relationship 1459: DET0179 — detects → T1069

**Source object:** [[01 ATT&CK/DET0179 - Behavioral Detection of Permission Groups Discovery|DET0179: Behavioral Detection of Permission Groups Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1069 - Permission Groups Discovery|T1069: Permission Groups Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35e5628c-ccc8-49c4-87db-2e683920288b`.
