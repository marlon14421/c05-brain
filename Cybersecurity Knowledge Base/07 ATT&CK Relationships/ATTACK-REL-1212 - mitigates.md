---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1013"
target_object: "T1496.003"
stix_relationship_id: "relationship--1bdf5794-9f6f-4d9a-9afd-542cefa858d0"
---
# Relationship 1212: M1013 — mitigates → T1496.003

**Source object:** [[01 ATT&CK/M1013 - Application Developer Guidance|M1013: Application Developer Guidance]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1496.003 - SMS Pumping|T1496.003: SMS Pumping]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider implementing CAPTCHA protection on forms that send messages via SMS.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1bdf5794-9f6f-4d9a-9afd-542cefa858d0`.
