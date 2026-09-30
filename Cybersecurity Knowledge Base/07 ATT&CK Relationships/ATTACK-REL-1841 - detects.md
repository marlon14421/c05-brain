---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0514"
target_object: "T1068"
stix_relationship_id: "relationship--d07fb93b-f652-4742-a99b-a4c99ff7b956"
---
# Relationship 1841: DET0514 — detects → T1068

**Source object:** [[01 ATT&CK/DET0514 - Detection Strategy for Exploitation for Privilege Escalation|DET0514: Detection Strategy for Exploitation for Privilege Escalation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d07fb93b-f652-4742-a99b-a4c99ff7b956`.
