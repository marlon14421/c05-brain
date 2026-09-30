---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0101"
target_object: "T1059.011"
stix_relationship_id: "relationship--1561faed-2a13-4416-9cab-06159d35f746"
---
# Relationship 1663: DET0101 — detects → T1059.011

**Source object:** [[01 ATT&CK/DET0101 - Detection Strategy for Lua Scripting Abuse|DET0101: Detection Strategy for Lua Scripting Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1059.011 - Lua|T1059.011: Lua]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1561faed-2a13-4416-9cab-06159d35f746`.
