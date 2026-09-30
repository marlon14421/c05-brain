---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1035"
target_object: "T1021.001"
stix_relationship_id: "relationship--375d3b8b-0e1b-4d3b-b31f-43b0e98436a5"
---
# Relationship 0460: M1035 — mitigates → T1021.001

**Source object:** [[01 ATT&CK/M1035 - Limit Access to Resource Over Network|M1035: Limit Access to Resource Over Network]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1021.001 - Remote Desktop Protocol|T1021.001: Remote Desktop Protocol]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use remote desktop gateways.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--375d3b8b-0e1b-4d3b-b31f-43b0e98436a5`.
