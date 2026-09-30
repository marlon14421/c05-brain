---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0204"
target_object: "T1547.010"
stix_relationship_id: "relationship--c30dfb12-041c-49d3-bce4-a7de82917d1e"
---
# Relationship 1821: DET0204 — detects → T1547.010

**Source object:** [[01 ATT&CK/DET0204 - Detection Strategy for T1547.010 – Port Monitor DLL Persistence via spoolsv.exe (Wind|DET0204: Detection Strategy for T1547.010 – Port Monitor DLL Persistence via spoolsv.exe (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.010 - Port Monitors|T1547.010: Port Monitors]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c30dfb12-041c-49d3-bce4-a7de82917d1e`.
