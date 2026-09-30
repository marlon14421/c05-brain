---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0344"
target_object: "T1027.011"
stix_relationship_id: "relationship--46d67e25-2b9d-4848-b251-9c885658d80e"
---
# Relationship 1613: DET0344 — detects → T1027.011

**Source object:** [[01 ATT&CK/DET0344 - Detection Strategy for Fileless Storage via Registry, WMI, and Shared Memory|DET0344: Detection Strategy for Fileless Storage via Registry, WMI, and Shared Memory]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.011 - Fileless Storage|T1027.011: Fileless Storage]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--46d67e25-2b9d-4848-b251-9c885658d80e`.
