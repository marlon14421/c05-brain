---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0538"
target_object: "T1572"
stix_relationship_id: "relationship--fab7fca5-a36a-481c-a110-4c2abc2af359"
---
# Relationship 2103: DET0538 — detects → T1572

**Source object:** [[01 ATT&CK/DET0538 - Detection Strategy for Protocol Tunneling accross OS platforms|DET0538: Detection Strategy for Protocol Tunneling accross OS platforms.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1572 - Protocol Tunneling|T1572: Protocol Tunneling]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fab7fca5-a36a-481c-a110-4c2abc2af359`.
