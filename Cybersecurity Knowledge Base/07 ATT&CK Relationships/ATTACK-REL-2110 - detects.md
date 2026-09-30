---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0366"
target_object: "T1036.007"
stix_relationship_id: "relationship--c0c7a062-29b4-4ca1-971c-d0a8982d27a7"
---
# Relationship 2110: DET0366 — detects → T1036.007

**Source object:** [[01 ATT&CK/DET0366 - Detection Strategy for Double File Extension Masquerading|DET0366: Detection Strategy for Double File Extension Masquerading]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1036.007 - Double File Extension|T1036.007: Double File Extension]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0c7a062-29b4-4ca1-971c-d0a8982d27a7`.
