---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0298"
target_object: "T1560.001"
stix_relationship_id: "relationship--c7013933-c677-45a7-9e5d-b3e76d2cd089"
---
# Relationship 1862: DET0298 — detects → T1560.001

**Source object:** [[01 ATT&CK/DET0298 - Detect Archiving via Utility (T1560.001)|DET0298: Detect Archiving via Utility (T1560.001)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7013933-c677-45a7-9e5d-b3e76d2cd089`.
