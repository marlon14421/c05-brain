---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0122"
target_object: "T1547.003"
stix_relationship_id: "relationship--0b8b7d52-f626-4477-917c-74138035e5db"
---
# Relationship 2119: DET0122 — detects → T1547.003

**Source object:** [[01 ATT&CK/DET0122 - Detect Abuse of Windows Time Providers for Persistence|DET0122: Detect Abuse of Windows Time Providers for Persistence]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.003 - Time Providers|T1547.003: Time Providers]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b8b7d52-f626-4477-917c-74138035e5db`.
