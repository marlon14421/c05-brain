---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0375"
target_object: "T1546.017"
stix_relationship_id: "relationship--ead170a2-4988-4931-a899-0ff26cd815a0"
---
# Relationship 1760: DET0375 — detects → T1546.017

**Source object:** [[01 ATT&CK/DET0375 - Detection Strategy for T1546.017 - Udev Rules (Linux)|DET0375: Detection Strategy for T1546.017 - Udev Rules (Linux)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.017 - Udev Rules|T1546.017: Udev Rules]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ead170a2-4988-4931-a899-0ff26cd815a0`.
