---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0064"
target_object: "T1574.009"
stix_relationship_id: "relationship--b55f3cb7-c47c-4b8d-91b2-cb91da1ee73d"
---
# Relationship 1856: DET0064 — detects → T1574.009

**Source object:** [[01 ATT&CK/DET0064 - Detection Strategy for Hijack Execution Flow through Path Interception by Unquoted Pa|DET0064: Detection Strategy for Hijack Execution Flow through Path Interception by Unquoted Path]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574.009 - Path Interception by Unquoted Path|T1574.009: Path Interception by Unquoted Path]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b55f3cb7-c47c-4b8d-91b2-cb91da1ee73d`.
