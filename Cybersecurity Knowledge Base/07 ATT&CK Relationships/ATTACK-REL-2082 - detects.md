---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0316"
target_object: "T1561.001"
stix_relationship_id: "relationship--bd2a2912-3948-4c1e-aeb6-cee23227a6ca"
---
# Relationship 2082: DET0316 — detects → T1561.001

**Source object:** [[01 ATT&CK/DET0316 - Detection Strategy for Disk Content Wipe via Direct Access and Overwrite|DET0316: Detection Strategy for Disk Content Wipe via Direct Access and Overwrite]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd2a2912-3948-4c1e-aeb6-cee23227a6ca`.
