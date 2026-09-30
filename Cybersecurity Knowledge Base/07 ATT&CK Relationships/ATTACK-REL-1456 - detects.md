---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0864"
target_object: "T1584.007"
stix_relationship_id: "relationship--fa88e227-3d53-4a52-a608-1cf4f7ef050e"
---
# Relationship 1456: DET0864 — detects → T1584.007

**Source object:** [[01 ATT&CK/DET0864 - Detection of Serverless|DET0864: Detection of Serverless]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1584.007 - Serverless|T1584.007: Serverless]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa88e227-3d53-4a52-a608-1cf4f7ef050e`.
