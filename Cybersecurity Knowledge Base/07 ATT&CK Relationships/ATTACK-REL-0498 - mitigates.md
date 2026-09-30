---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1025"
target_object: "T1003"
stix_relationship_id: "relationship--a6f27258-cf6a-4d75-a3f0-5de085d528d2"
---
# Relationship 0498: M1025 — mitigates → T1003

**Source object:** [[01 ATT&CK/M1025 - Privileged Process Integrity|M1025: Privileged Process Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1003 - OS Credential Dumping|T1003: OS Credential Dumping]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

On Windows 8.1 and Windows Server 2012 R2, enable Protected Process Light for LSA.(Citation: Microsoft LSA)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6f27258-cf6a-4d75-a3f0-5de085d528d2`.
