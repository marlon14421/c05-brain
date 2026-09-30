---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1029"
target_object: "T1070.009"
stix_relationship_id: "relationship--bb01eb87-696e-496d-9fb9-5abe60b57b12"
---
# Relationship 0662: M1029 — mitigates → T1070.009

**Source object:** [[01 ATT&CK/M1029 - Remote Data Storage|M1029: Remote Data Storage]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1070.009 - Clear Persistence|T1070.009: Clear Persistence]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Automatically forward events to a log server or data repository to prevent conditions in which the adversary can locate and manipulate data on the local system. When possible, minimize time delay on event reporting to avoid prolonged storage on the local system.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb01eb87-696e-496d-9fb9-5abe60b57b12`.
