---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1056"
target_object: "T1588.004"
stix_relationship_id: "relationship--0d600c05-c617-46f4-947f-cdd6ca56d494"
---
# Relationship 0001: M1056 — mitigates → T1588.004

**Source object:** [[01 ATT&CK/M1056 - Pre-compromise|M1056: Pre-compromise]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1588.004 - Digital Certificates|T1588.004: Digital Certificates]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

This technique cannot be easily mitigated with preventive controls since it is based on behaviors performed outside of the scope of enterprise defenses and controls.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d600c05-c617-46f4-947f-cdd6ca56d494`.
