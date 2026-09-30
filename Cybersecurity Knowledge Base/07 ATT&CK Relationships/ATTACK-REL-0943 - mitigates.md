---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1025"
target_object: "T1556.001"
stix_relationship_id: "relationship--83f862a4-cfac-4665-8ff8-60df70a636f4"
---
# Relationship 0943: M1025 — mitigates → T1556.001

**Source object:** [[01 ATT&CK/M1025 - Privileged Process Integrity|M1025: Privileged Process Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1556.001 - Domain Controller Authentication|T1556.001: Domain Controller Authentication]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enabled features, such as Protected Process Light (PPL), for LSA.(Citation: Microsoft LSA)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83f862a4-cfac-4665-8ff8-60df70a636f4`.
