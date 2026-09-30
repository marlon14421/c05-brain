---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0208"
target_object: "T1499"
stix_relationship_id: "relationship--cbf233dc-3732-45d3-b89a-b7df7dc1d2ff"
---
# Relationship 2042: DET0208 — detects → T1499

**Source object:** [[01 ATT&CK/DET0208 - Endpoint Resource Saturation and Crash Pattern Detection Across Platforms|DET0208: Endpoint Resource Saturation and Crash Pattern Detection Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1499 - Endpoint Denial of Service|T1499: Endpoint Denial of Service]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbf233dc-3732-45d3-b89a-b7df7dc1d2ff`.
