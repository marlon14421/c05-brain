---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1033"
target_object: "T1059.011"
stix_relationship_id: "relationship--3c9ea8d0-d8b4-4ddd-89d8-47d38b057736"
---
# Relationship 0645: M1033 — mitigates → T1059.011

**Source object:** [[01 ATT&CK/M1033 - Limit Software Installation|M1033: Limit Software Installation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1059.011 - Lua|T1059.011: Lua]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent users from installing Lua where not required.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c9ea8d0-d8b4-4ddd-89d8-47d38b057736`.
