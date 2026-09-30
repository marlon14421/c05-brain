---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0917"
target_object: "T1683.001"
stix_relationship_id: "relationship--a92a20f6-e593-4c49-a75c-151041659a65"
---
# Relationship 1810: DET0917 — detects → T1683.001

**Source object:** [[01 ATT&CK/DET0917 - Detection of Written Content|DET0917: Detection of Written Content]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1683.001 - Written Content|T1683.001: Written Content]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a92a20f6-e593-4c49-a75c-151041659a65`.
