---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0574"
target_object: "T1018"
stix_relationship_id: "relationship--1a34cffa-3bac-4b7f-a011-4d09aca360b6"
---
# Relationship 1503: DET0574 — detects → T1018

**Source object:** [[01 ATT&CK/DET0574 - Detection Strategy for Remote System Enumeration Behavior|DET0574: Detection Strategy for Remote System Enumeration Behavior]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a34cffa-3bac-4b7f-a011-4d09aca360b6`.
