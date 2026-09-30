---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0299"
target_object: "T1222"
stix_relationship_id: "relationship--3f78696b-0ec4-4d0c-9e65-5bb26ee3ebe7"
---
# Relationship 1523: DET0299 — detects → T1222

**Source object:** [[01 ATT&CK/DET0299 - Multi-Platform File and Directory Permissions Modification Detection Strategy|DET0299: Multi-Platform File and Directory Permissions Modification Detection Strategy]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1222 - File and Directory Permissions Modification|T1222: File and Directory Permissions Modification]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3f78696b-0ec4-4d0c-9e65-5bb26ee3ebe7`.
