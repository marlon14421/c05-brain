---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1025"
target_object: "T1003.001"
stix_relationship_id: "relationship--871cce82-c9fe-47e3-bd03-94a29a295f90"
---
# Relationship 0103: M1025 — mitigates → T1003.001

**Source object:** [[01 ATT&CK/M1025 - Privileged Process Integrity|M1025: Privileged Process Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

On Windows 8.1 and Windows Server 2012 R2, enable Protected Process Light for LSA.(Citation: Microsoft LSA)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--871cce82-c9fe-47e3-bd03-94a29a295f90`.
