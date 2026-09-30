---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0817"
target_object: "T1595.001"
stix_relationship_id: "relationship--a2282a7b-b0b0-4b49-a9cf-9176990e4ec9"
---
# Relationship 2094: DET0817 — detects → T1595.001

**Source object:** [[01 ATT&CK/DET0817 - Detection of Scanning IP Blocks|DET0817: Detection of Scanning IP Blocks]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1595.001 - Scanning IP Blocks|T1595.001: Scanning IP Blocks]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a2282a7b-b0b0-4b49-a9cf-9176990e4ec9`.
