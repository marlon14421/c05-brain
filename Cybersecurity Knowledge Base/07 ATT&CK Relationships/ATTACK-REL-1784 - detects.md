---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0150"
target_object: "T1542.003"
stix_relationship_id: "relationship--13bb7165-bf8b-4c39-a356-9a5c765956ea"
---
# Relationship 1784: DET0150 — detects → T1542.003

**Source object:** [[01 ATT&CK/DET0150 - Detection Strategy for File Creation or Modification of Boot Files|DET0150: Detection Strategy for File Creation or Modification of Boot Files]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1542.003 - Bootkit|T1542.003: Bootkit]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13bb7165-bf8b-4c39-a356-9a5c765956ea`.
