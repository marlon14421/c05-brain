---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0233"
target_object: "T1602.002"
stix_relationship_id: "relationship--353de2e5-f6d0-4fc4-9fca-a8a7f1178346"
---
# Relationship 1963: DET0233 — detects → T1602.002

**Source object:** [[01 ATT&CK/DET0233 - Detection Strategy for Network Device Configuration Dump via Config Repositories|DET0233: Detection Strategy for Network Device Configuration Dump via Config Repositories]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1602.002 - Network Device Configuration Dump|T1602.002: Network Device Configuration Dump]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--353de2e5-f6d0-4fc4-9fca-a8a7f1178346`.
