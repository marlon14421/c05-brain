---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0569"
target_object: "T1601.002"
stix_relationship_id: "relationship--59bd78e7-9975-4340-be27-e1035d5529d8"
---
# Relationship 1809: DET0569 — detects → T1601.002

**Source object:** [[01 ATT&CK/DET0569 - Detection Strategy for Downgrade System Image on Network Devices|DET0569: Detection Strategy for Downgrade System Image on Network Devices]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1601.002 - Downgrade System Image|T1601.002: Downgrade System Image]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59bd78e7-9975-4340-be27-e1035d5529d8`.
