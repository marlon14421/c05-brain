---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1045"
target_object: "T1543"
stix_relationship_id: "relationship--a8e16c31-b516-4e64-ac0b-27d6b87bb82c"
---
# Relationship 0003: M1045 — mitigates → T1543

**Source object:** [[01 ATT&CK/M1045 - Code Signing|M1045: Code Signing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1543 - Create or Modify System Process|T1543: Create or Modify System Process]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enforce registration and execution of only legitimately signed service drivers where possible.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8e16c31-b516-4e64-ac0b-27d6b87bb82c`.
