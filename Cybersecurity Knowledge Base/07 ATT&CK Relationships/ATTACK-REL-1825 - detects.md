---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0043"
target_object: "T1614"
stix_relationship_id: "relationship--2a170a3a-d02a-48ff-a21c-23f373f8951f"
---
# Relationship 1825: DET0043 — detects → T1614

**Source object:** [[01 ATT&CK/DET0043 - Detection Strategy for System Location Discovery|DET0043: Detection Strategy for System Location Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1614 - System Location Discovery|T1614: System Location Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2a170a3a-d02a-48ff-a21c-23f373f8951f`.
