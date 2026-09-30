---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0595"
target_object: "T1211"
stix_relationship_id: "relationship--ef12e912-df4b-4359-b38a-24071b74414a"
---
# Relationship 2011: DET0595 — detects → T1211

**Source object:** [[01 ATT&CK/DET0595 - Detection Strategy for Exploitation for Stealth|DET0595: Detection Strategy for Exploitation for Stealth]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1211 - Exploitation for Stealth|T1211: Exploitation for Stealth]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef12e912-df4b-4359-b38a-24071b74414a`.
