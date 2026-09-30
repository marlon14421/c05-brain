---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0141"
target_object: "T1497.003"
stix_relationship_id: "relationship--77e5d090-d1f4-43aa-a068-b1c040875e48"
---
# Relationship 1709: DET0141 — detects → T1497.003

**Source object:** [[01 ATT&CK/DET0141 - Detect Time-Based Evasion via Sleep, Timer Loops, and Delayed Execution|DET0141: Detect Time-Based Evasion via Sleep, Timer Loops, and Delayed Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77e5d090-d1f4-43aa-a068-b1c040875e48`.
