---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0282"
target_object: "T1218.010"
stix_relationship_id: "relationship--6a5e3a15-ba2a-4836-ab40-8f5d8a3175bf"
---
# Relationship 2005: DET0282 — detects → T1218.010

**Source object:** [[01 ATT&CK/DET0282 - Detection Strategy for System Binary Proxy Execution- Regsvr32|DET0282: Detection Strategy for System Binary Proxy Execution: Regsvr32]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.010 - Regsvr32|T1218.010: Regsvr32]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a5e3a15-ba2a-4836-ab40-8f5d8a3175bf`.
