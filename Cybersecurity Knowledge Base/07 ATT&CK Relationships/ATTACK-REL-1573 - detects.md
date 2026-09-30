---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0364"
target_object: "T1047"
stix_relationship_id: "relationship--a1cc84bd-b7b2-40a8-a2d9-dc61fcde3cd1"
---
# Relationship 1573: DET0364 — detects → T1047

**Source object:** [[01 ATT&CK/DET0364 - Behavioral Detection Strategy for WMI Execution Abuse on Windows|DET0364: Behavioral Detection Strategy for WMI Execution Abuse on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a1cc84bd-b7b2-40a8-a2d9-dc61fcde3cd1`.
