---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0360"
target_object: "T1069.002"
stix_relationship_id: "relationship--cf165471-03e7-4e5f-bcfd-d712b92a9603"
---
# Relationship 2022: DET0360 — detects → T1069.002

**Source object:** [[01 ATT&CK/DET0360 - Behavioral Detection of Domain Group Discovery|DET0360: Behavioral Detection of Domain Group Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1069.002 - Domain Groups|T1069.002: Domain Groups]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cf165471-03e7-4e5f-bcfd-d712b92a9603`.
