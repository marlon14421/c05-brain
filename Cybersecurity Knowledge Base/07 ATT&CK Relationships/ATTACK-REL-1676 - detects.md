---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0108"
target_object: "T1132"
stix_relationship_id: "relationship--ebab4fe1-721f-40f5-9d24-cd8744bdc151"
---
# Relationship 1676: DET0108 — detects → T1132

**Source object:** [[01 ATT&CK/DET0108 - Detection Strategy for Data Encoding in C2 Channels|DET0108: Detection Strategy for Data Encoding in C2 Channels]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1132 - Data Encoding|T1132: Data Encoding]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ebab4fe1-721f-40f5-9d24-cd8744bdc151`.
