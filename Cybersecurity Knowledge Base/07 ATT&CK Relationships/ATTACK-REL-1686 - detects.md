---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0155"
target_object: "T1666"
stix_relationship_id: "relationship--04227e29-fba4-4b7d-9d2c-300814d5d2b2"
---
# Relationship 1686: DET0155 — detects → T1666

**Source object:** [[01 ATT&CK/DET0155 - Detection Strategy for Modify Cloud Resource Hierarchy|DET0155: Detection Strategy for Modify Cloud Resource Hierarchy]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1666 - Modify Cloud Resource Hierarchy|T1666: Modify Cloud Resource Hierarchy]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04227e29-fba4-4b7d-9d2c-300814d5d2b2`.
