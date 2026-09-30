---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0151"
target_object: "T1124"
stix_relationship_id: "relationship--a471c195-dbf1-4c84-a314-393189769d31"
---
# Relationship 1680: DET0151 — detects → T1124

**Source object:** [[01 ATT&CK/DET0151 - Behavior-chain, platform-aware detection strategy for T1124 System Time Discovery|DET0151: Behavior-chain, platform-aware detection strategy for T1124 System Time Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a471c195-dbf1-4c84-a314-393189769d31`.
