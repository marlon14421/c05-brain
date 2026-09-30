---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0428"
target_object: "T1564.013"
stix_relationship_id: "relationship--4e46ebb7-87d4-49b1-b0f8-93d897b0ab01"
---
# Relationship 1874: DET0428 — detects → T1564.013

**Source object:** [[01 ATT&CK/DET0428 - Detection Strategy for Bind Mounts on Linux|DET0428: Detection Strategy for Bind Mounts on Linux]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1564.013 - Bind Mounts|T1564.013: Bind Mounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e46ebb7-87d4-49b1-b0f8-93d897b0ab01`.
