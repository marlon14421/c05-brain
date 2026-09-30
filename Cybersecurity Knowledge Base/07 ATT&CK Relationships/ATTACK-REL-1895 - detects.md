---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0565"
target_object: "T1614.001"
stix_relationship_id: "relationship--f5a7f182-3a05-43c4-aa12-b3d0bdbbde38"
---
# Relationship 1895: DET0565 — detects → T1614.001

**Source object:** [[01 ATT&CK/DET0565 - Detection Strategy for System Language Discovery|DET0565: Detection Strategy for System Language Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5a7f182-3a05-43c4-aa12-b3d0bdbbde38`.
