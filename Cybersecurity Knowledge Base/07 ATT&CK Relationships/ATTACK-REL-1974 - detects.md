---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0301"
target_object: "T1091"
stix_relationship_id: "relationship--9421f9f1-c10a-49bf-991f-1df07b8953f0"
---
# Relationship 1974: DET0301 — detects → T1091

**Source object:** [[01 ATT&CK/DET0301 - Removable Media Execution Chain Detection via File and Process Activity|DET0301: Removable Media Execution Chain Detection via File and Process Activity]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1091 - Replication Through Removable Media|T1091: Replication Through Removable Media]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9421f9f1-c10a-49bf-991f-1df07b8953f0`.
