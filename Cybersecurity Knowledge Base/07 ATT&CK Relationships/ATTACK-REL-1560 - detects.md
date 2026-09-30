---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0200"
target_object: "T1202"
stix_relationship_id: "relationship--8bb1b5ae-824e-41f2-b3a3-f852e8c9bffe"
---
# Relationship 1560: DET0200 — detects → T1202

**Source object:** [[01 ATT&CK/DET0200 - Indirect Command Execution – Windows utility abuse behavior chain|DET0200: Indirect Command Execution – Windows utility abuse behavior chain]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1202 - Indirect Command Execution|T1202: Indirect Command Execution]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8bb1b5ae-824e-41f2-b3a3-f852e8c9bffe`.
