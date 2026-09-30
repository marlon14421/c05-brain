---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0088"
target_object: "T1518.002"
stix_relationship_id: "relationship--143dc28d-6b45-4a97-833f-e47469216e0b"
---
# Relationship 1979: DET0088 — detects → T1518.002

**Source object:** [[01 ATT&CK/DET0088 - Backup Software Discovery via CLI, Registry, and Process Inspection (T1518.002)|DET0088: Backup Software Discovery via CLI, Registry, and Process Inspection (T1518.002)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1518.002 - Backup Software Discovery|T1518.002: Backup Software Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--143dc28d-6b45-4a97-833f-e47469216e0b`.
