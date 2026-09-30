---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0268"
target_object: "T1560.002"
stix_relationship_id: "relationship--61d0daa0-1566-445b-b9ef-1fc5152ab8f7"
---
# Relationship 1943: DET0268 — detects → T1560.002

**Source object:** [[01 ATT&CK/DET0268 - Detect Archiving via Library (T1560.002)|DET0268: Detect Archiving via Library (T1560.002)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1560.002 - Archive via Library|T1560.002: Archive via Library]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--61d0daa0-1566-445b-b9ef-1fc5152ab8f7`.
