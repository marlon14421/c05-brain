---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0102"
target_object: "T1056"
stix_relationship_id: "relationship--66b2b5b7-2947-46b5-a4b5-b98eea8c793c"
---
# Relationship 1491: DET0102 — detects → T1056

**Source object:** [[01 ATT&CK/DET0102 - Behavioral Detection of Input Capture Across Platforms|DET0102: Behavioral Detection of Input Capture Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1056 - Input Capture|T1056: Input Capture]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66b2b5b7-2947-46b5-a4b5-b98eea8c793c`.
