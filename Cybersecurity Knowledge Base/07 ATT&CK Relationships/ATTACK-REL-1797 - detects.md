---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0338"
target_object: "T1550"
stix_relationship_id: "relationship--a152e0f1-2588-4c93-aeb8-78a596e153e0"
---
# Relationship 1797: DET0338 — detects → T1550

**Source object:** [[01 ATT&CK/DET0338 - Behavioral Detection Strategy for Use Alternate Authentication Material (T1550)|DET0338: Behavioral Detection Strategy for Use Alternate Authentication Material (T1550)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1550 - Use Alternate Authentication Material|T1550: Use Alternate Authentication Material]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a152e0f1-2588-4c93-aeb8-78a596e153e0`.
