---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0072"
target_object: "T1037.001"
stix_relationship_id: "relationship--aa3ea0d1-4bbf-400d-9e36-9369288de47e"
---
# Relationship 1993: DET0072 — detects → T1037.001

**Source object:** [[01 ATT&CK/DET0072 - Detect Logon Script Modifications and Execution|DET0072: Detect Logon Script Modifications and Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1037.001 - Logon Script (Windows)|T1037.001: Logon Script (Windows)]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aa3ea0d1-4bbf-400d-9e36-9369288de47e`.
