---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0212"
target_object: "T1505.005"
stix_relationship_id: "relationship--1b08f84f-6a97-4f3c-a5e6-4b99e09d9575"
---
# Relationship 1569: DET0212 — detects → T1505.005

**Source object:** [[01 ATT&CK/DET0212 - Detection Strategy for T1505.005 – Terminal Services DLL Modification (Windows)|DET0212: Detection Strategy for T1505.005 – Terminal Services DLL Modification (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1505.005 - Terminal Services DLL|T1505.005: Terminal Services DLL]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b08f84f-6a97-4f3c-a5e6-4b99e09d9575`.
