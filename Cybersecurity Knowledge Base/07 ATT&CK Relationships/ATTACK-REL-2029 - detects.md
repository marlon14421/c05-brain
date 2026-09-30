---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0097"
target_object: "T1010"
stix_relationship_id: "relationship--5d3892e4-5a49-482a-929b-883fb2cdb765"
---
# Relationship 2029: DET0097 — detects → T1010

**Source object:** [[01 ATT&CK/DET0097 - Detection of Application Window Enumeration via API or Scripting|DET0097: Detection of Application Window Enumeration via API or Scripting]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1010 - Application Window Discovery|T1010: Application Window Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d3892e4-5a49-482a-929b-883fb2cdb765`.
