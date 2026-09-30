---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0536"
target_object: "T1669"
stix_relationship_id: "relationship--f5fef0bf-a8a0-41e2-b46a-71255836928d"
---
# Relationship 2003: DET0536 — detects → T1669

**Source object:** [[01 ATT&CK/DET0536 - Detection Strategy for Wi-Fi Networks|DET0536: Detection Strategy for Wi-Fi Networks]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1669 - Wi-Fi Networks|T1669: Wi-Fi Networks]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5fef0bf-a8a0-41e2-b46a-71255836928d`.
