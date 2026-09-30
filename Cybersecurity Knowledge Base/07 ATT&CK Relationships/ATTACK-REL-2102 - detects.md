---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0065"
target_object: "T1609"
stix_relationship_id: "relationship--643dc681-2238-46b5-8e00-590eecd638af"
---
# Relationship 2102: DET0065 — detects → T1609

**Source object:** [[01 ATT&CK/DET0065 - Detection Strategy for Container Administration Command Abuse|DET0065: Detection Strategy for Container Administration Command Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1609 - Container Administration Command|T1609: Container Administration Command]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--643dc681-2238-46b5-8e00-590eecd638af`.
