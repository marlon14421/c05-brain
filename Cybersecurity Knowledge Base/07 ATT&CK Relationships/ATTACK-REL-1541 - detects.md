---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0582"
target_object: "T1542.005"
stix_relationship_id: "relationship--916d2916-f484-4d91-a454-1822f0b39769"
---
# Relationship 1541: DET0582 — detects → T1542.005

**Source object:** [[01 ATT&CK/DET0582 - Detection Strategy for T1542.005 Pre-OS Boot- TFTP Boot|DET0582: Detection Strategy for T1542.005 Pre-OS Boot: TFTP Boot]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1542.005 - TFTP Boot|T1542.005: TFTP Boot]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--916d2916-f484-4d91-a454-1822f0b39769`.
