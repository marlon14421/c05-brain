---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0371"
target_object: "T1622"
stix_relationship_id: "relationship--e6bda228-b1c4-4fc7-b877-457557628832"
---
# Relationship 2016: DET0371 — detects → T1622

**Source object:** [[01 ATT&CK/DET0371 - Detection Strategy for Debugger Evasion (T1622)|DET0371: Detection Strategy for Debugger Evasion (T1622)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1622 - Debugger Evasion|T1622: Debugger Evasion]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6bda228-b1c4-4fc7-b877-457557628832`.
