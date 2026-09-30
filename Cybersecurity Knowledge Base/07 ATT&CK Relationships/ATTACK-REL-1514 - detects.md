---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0497"
target_object: "T1685"
stix_relationship_id: "relationship--ce5ab389-680d-4055-91a8-1111e5530bfa"
---
# Relationship 1514: DET0497 — detects → T1685

**Source object:** [[01 ATT&CK/DET0497 - Detection of Defense Impairment through Disabled or Modified Tools across OS Platform|DET0497: Detection of Defense Impairment through Disabled or Modified Tools across OS Platforms.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce5ab389-680d-4055-91a8-1111e5530bfa`.
