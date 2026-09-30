---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0202"
target_object: "T1059.003"
stix_relationship_id: "relationship--ebad757b-f342-4ba1-8695-df0c69952904"
---
# Relationship 1494: DET0202 — detects → T1059.003

**Source object:** [[01 ATT&CK/DET0202 - Behavioral Detection of Windows Command Shell Execution|DET0202: Behavioral Detection of Windows Command Shell Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ebad757b-f342-4ba1-8695-df0c69952904`.
