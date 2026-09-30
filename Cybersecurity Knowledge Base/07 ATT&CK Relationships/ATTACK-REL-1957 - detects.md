---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0106"
target_object: "T1055.002"
stix_relationship_id: "relationship--791e4c52-5ed6-4c01-be8c-33e264a749f4"
---
# Relationship 1957: DET0106 — detects → T1055.002

**Source object:** [[01 ATT&CK/DET0106 - Behavioral Detection of PE Injection via Remote Memory Mapping|DET0106: Behavioral Detection of PE Injection via Remote Memory Mapping]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1055.002 - Portable Executable Injection|T1055.002: Portable Executable Injection]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--791e4c52-5ed6-4c01-be8c-33e264a749f4`.
