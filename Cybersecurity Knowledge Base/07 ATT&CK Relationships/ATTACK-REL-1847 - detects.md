---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0100"
target_object: "T1055.004"
stix_relationship_id: "relationship--ae7a893f-f309-426e-9486-56669c6ad7b9"
---
# Relationship 1847: DET0100 — detects → T1055.004

**Source object:** [[01 ATT&CK/DET0100 - Behavioral Detection of Asynchronous Procedure Call (APC) Injection via Remote Thread|DET0100: Behavioral Detection of Asynchronous Procedure Call (APC) Injection via Remote Thread Queuing]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1055.004 - Asynchronous Procedure Call|T1055.004: Asynchronous Procedure Call]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae7a893f-f309-426e-9486-56669c6ad7b9`.
