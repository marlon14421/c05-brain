---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0529"
target_object: "T1106"
stix_relationship_id: "relationship--dc9d1fc2-471b-49c3-b372-9703fd5125f4"
---
# Relationship 2059: DET0529 — detects → T1106

**Source object:** [[01 ATT&CK/DET0529 - Behavioral Detection of Native API Invocation via Unusual DLL Loads and Direct Syscal|DET0529: Behavioral Detection of Native API Invocation via Unusual DLL Loads and Direct Syscalls]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dc9d1fc2-471b-49c3-b372-9703fd5125f4`.
