---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0855"
target_object: "T1591.002"
stix_relationship_id: "relationship--0dca67c1-8633-4098-bcae-470f710bff79"
---
# Relationship 2063: DET0855 — detects → T1591.002

**Source object:** [[01 ATT&CK/DET0855 - Detection of Business Relationships|DET0855: Detection of Business Relationships]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1591.002 - Business Relationships|T1591.002: Business Relationships]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0dca67c1-8633-4098-bcae-470f710bff79`.
