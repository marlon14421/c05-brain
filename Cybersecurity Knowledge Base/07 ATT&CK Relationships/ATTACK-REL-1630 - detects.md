---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0874"
target_object: "T1584.004"
stix_relationship_id: "relationship--01da542d-e185-4495-b40b-fc9b4068a834"
---
# Relationship 1630: DET0874 — detects → T1584.004

**Source object:** [[01 ATT&CK/DET0874 - Detection of Server|DET0874: Detection of Server]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1584.004 - Server|T1584.004: Server]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--01da542d-e185-4495-b40b-fc9b4068a834`.
