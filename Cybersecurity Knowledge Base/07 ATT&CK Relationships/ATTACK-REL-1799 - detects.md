---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0129"
target_object: "T1087.002"
stix_relationship_id: "relationship--0e8bdd63-70d5-43c8-a56d-b66d54e7b043"
---
# Relationship 1799: DET0129 — detects → T1087.002

**Source object:** [[01 ATT&CK/DET0129 - Domain Account Enumeration Across Platforms|DET0129: Domain Account Enumeration Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e8bdd63-70d5-43c8-a56d-b66d54e7b043`.
