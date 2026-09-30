---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0849"
target_object: "T1591.003"
stix_relationship_id: "relationship--f57c4831-c37d-47c1-b3c5-c11cf2da515a"
---
# Relationship 2021: DET0849 — detects → T1591.003

**Source object:** [[01 ATT&CK/DET0849 - Detection of Identify Business Tempo|DET0849: Detection of Identify Business Tempo]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1591.003 - Identify Business Tempo|T1591.003: Identify Business Tempo]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f57c4831-c37d-47c1-b3c5-c11cf2da515a`.
