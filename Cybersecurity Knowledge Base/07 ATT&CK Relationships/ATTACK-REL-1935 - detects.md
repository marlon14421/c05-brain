---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0517"
target_object: "T1574.014"
stix_relationship_id: "relationship--66f784b0-ff60-4199-ae52-2bc2679bec1e"
---
# Relationship 1935: DET0517 — detects → T1574.014

**Source object:** [[01 ATT&CK/DET0517 - Detection Strategy for Hijack Execution Flow through the AppDomainManager on Windows|DET0517: Detection Strategy for Hijack Execution Flow through the AppDomainManager on Windows.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574.014 - AppDomainManager|T1574.014: AppDomainManager]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66f784b0-ff60-4199-ae52-2bc2679bec1e`.
