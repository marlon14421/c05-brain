---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0091"
target_object: "T1027.007"
stix_relationship_id: "relationship--c032d3e6-73e7-4918-9323-ee7c06a58cfc"
---
# Relationship 1942: DET0091 — detects → T1027.007

**Source object:** [[01 ATT&CK/DET0091 - Detection Strategy for Dynamic API Resolution via Hash-Based Function Lookups|DET0091: Detection Strategy for Dynamic API Resolution via Hash-Based Function Lookups]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.007 - Dynamic API Resolution|T1027.007: Dynamic API Resolution]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c032d3e6-73e7-4918-9323-ee7c06a58cfc`.
