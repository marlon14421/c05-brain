---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0035"
target_object: "T1102.002"
stix_relationship_id: "relationship--835d55ac-48f3-407e-a4a3-7cfd1437b0d7"
---
# Relationship 2136: DET0035 — detects → T1102.002

**Source object:** [[01 ATT&CK/DET0035 - Detect Bidirectional Web Service C2 Channels via Process & Network Correlation|DET0035: Detect Bidirectional Web Service C2 Channels via Process & Network Correlation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--835d55ac-48f3-407e-a4a3-7cfd1437b0d7`.
