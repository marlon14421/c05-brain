---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0435"
target_object: "T1574.006"
stix_relationship_id: "relationship--7cc0a19d-6627-483b-9de1-a723124fa736"
---
# Relationship 1624: DET0435 — detects → T1574.006

**Source object:** [[01 ATT&CK/DET0435 - Detection Strategy for Hijack Execution Flow- Dynamic Linker Hijacking|DET0435: Detection Strategy for Hijack Execution Flow: Dynamic Linker Hijacking]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574.006 - Dynamic Linker Hijacking|T1574.006: Dynamic Linker Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7cc0a19d-6627-483b-9de1-a723124fa736`.
