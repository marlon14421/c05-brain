---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0182"
target_object: "T1135"
stix_relationship_id: "relationship--1170753c-b8d9-4bd8-a3d7-e09882b53897"
---
# Relationship 1536: DET0182 — detects → T1135

**Source object:** [[01 ATT&CK/DET0182 - Behavior-chain detection for T1135 Network Share Discovery across Windows, Linux, and|DET0182: Behavior-chain detection for T1135 Network Share Discovery across Windows, Linux, and macOS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1170753c-b8d9-4bd8-a3d7-e09882b53897`.
