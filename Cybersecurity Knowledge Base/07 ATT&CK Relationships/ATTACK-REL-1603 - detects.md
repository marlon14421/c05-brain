---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0198"
target_object: "T1552.007"
stix_relationship_id: "relationship--5f89a15d-ac8b-49ab-9410-dbc9f5931f05"
---
# Relationship 1603: DET0198 — detects → T1552.007

**Source object:** [[01 ATT&CK/DET0198 - Detect Abuse of Container APIs for Credential Access|DET0198: Detect Abuse of Container APIs for Credential Access]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1552.007 - Container API|T1552.007: Container API]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f89a15d-ac8b-49ab-9410-dbc9f5931f05`.
