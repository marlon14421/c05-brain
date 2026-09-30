---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0456"
target_object: "T1134.002"
stix_relationship_id: "relationship--76d197d3-8ed8-4e40-9245-a30a29229131"
---
# Relationship 1824: DET0456 — detects → T1134.002

**Source object:** [[01 ATT&CK/DET0456 - Behavior-chain detection for T1134.002 Create Process with Token (Windows)|DET0456: Behavior-chain detection for T1134.002 Create Process with Token (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1134.002 - Create Process with Token|T1134.002: Create Process with Token]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76d197d3-8ed8-4e40-9245-a30a29229131`.
