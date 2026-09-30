---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0175"
target_object: "T1542.004"
stix_relationship_id: "relationship--99ff6f4d-187b-4e52-8ad6-b9e471ae96fb"
---
# Relationship 1532: DET0175 — detects → T1542.004

**Source object:** [[01 ATT&CK/DET0175 - Detection Strategy for T1542.004 Pre-OS Boot- ROMMONkit|DET0175: Detection Strategy for T1542.004 Pre-OS Boot: ROMMONkit]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1542.004 - ROMMONkit|T1542.004: ROMMONkit]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--99ff6f4d-187b-4e52-8ad6-b9e471ae96fb`.
