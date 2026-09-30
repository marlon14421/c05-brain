---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0392"
target_object: "T1518"
stix_relationship_id: "relationship--c4196ba6-3955-4c94-8224-a8d12708e248"
---
# Relationship 1772: DET0392 — detects → T1518

**Source object:** [[01 ATT&CK/DET0392 - Multi-Platform Software Discovery Behavior Chain|DET0392: Multi-Platform Software Discovery Behavior Chain]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4196ba6-3955-4c94-8224-a8d12708e248`.
