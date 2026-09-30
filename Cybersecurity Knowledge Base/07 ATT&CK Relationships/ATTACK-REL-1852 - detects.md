---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0292"
target_object: "T1036.006"
stix_relationship_id: "relationship--ca314796-7dc4-401d-99bd-f3624f025832"
---
# Relationship 1852: DET0292 — detects → T1036.006

**Source object:** [[01 ATT&CK/DET0292 - Masquerading via Space After Filename - Behavioral Detection Strategy|DET0292: Masquerading via Space After Filename - Behavioral Detection Strategy]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1036.006 - Space after Filename|T1036.006: Space after Filename]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ca314796-7dc4-401d-99bd-f3624f025832`.
