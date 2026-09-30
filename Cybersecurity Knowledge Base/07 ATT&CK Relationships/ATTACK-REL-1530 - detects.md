---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0052"
target_object: "T1548.003"
stix_relationship_id: "relationship--03a824e7-d39f-4286-9833-525b81bc63d4"
---
# Relationship 1530: DET0052 — detects → T1548.003

**Source object:** [[01 ATT&CK/DET0052 - Behavioral Detection Strategy for Abuse of Sudo and Sudo Caching|DET0052: Behavioral Detection Strategy for Abuse of Sudo and Sudo Caching]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1548.003 - Sudo and Sudo Caching|T1548.003: Sudo and Sudo Caching]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03a824e7-d39f-4286-9833-525b81bc63d4`.
