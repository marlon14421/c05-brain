---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0201"
target_object: "T1574.001"
stix_relationship_id: "relationship--21fcc54f-0e35-4b2f-8c97-294f0f345d3f"
---
# Relationship 1667: DET0201 — detects → T1574.001

**Source object:** [[01 ATT&CK/DET0201 - Detection Strategy for Hijack Execution Flow for DLLs|DET0201: Detection Strategy for Hijack Execution Flow for DLLs]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21fcc54f-0e35-4b2f-8c97-294f0f345d3f`.
