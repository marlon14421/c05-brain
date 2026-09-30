---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0312"
target_object: "T1547.014"
stix_relationship_id: "relationship--afb6aa42-751c-47fe-b955-0733344a444f"
---
# Relationship 1836: DET0312 — detects → T1547.014

**Source object:** [[01 ATT&CK/DET0312 - Detect Active Setup Persistence via StubPath Execution|DET0312: Detect Active Setup Persistence via StubPath Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.014 - Active Setup|T1547.014: Active Setup]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--afb6aa42-751c-47fe-b955-0733344a444f`.
