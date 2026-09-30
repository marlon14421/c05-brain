---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0098"
target_object: "T1197"
stix_relationship_id: "relationship--0967546e-b205-4de2-92eb-2847cb4ad94e"
---
# Relationship 1735: DET0098 — detects → T1197

**Source object:** [[01 ATT&CK/DET0098 - Detect abuse of Windows BITS Jobs for download, execution and persistence|DET0098: Detect abuse of Windows BITS Jobs for download, execution and persistence]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1197 - BITS Jobs|T1197: BITS Jobs]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0967546e-b205-4de2-92eb-2847cb4ad94e`.
