---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0355"
target_object: "T1667"
stix_relationship_id: "relationship--f534e0c4-f16c-45cd-a4cb-be462c69fc0a"
---
# Relationship 1690: DET0355 — detects → T1667

**Source object:** [[01 ATT&CK/DET0355 - Detection Strategy for Email Bombing|DET0355: Detection Strategy for Email Bombing]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1667 - Email Bombing|T1667: Email Bombing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f534e0c4-f16c-45cd-a4cb-be462c69fc0a`.
