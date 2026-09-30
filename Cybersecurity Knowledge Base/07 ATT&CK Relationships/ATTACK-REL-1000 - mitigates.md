---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1546.003"
stix_relationship_id: "relationship--a8e5b5ae-85ca-48da-b3a0-36da1162034d"
---
# Relationship 1000: M1026 — mitigates → T1546.003

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1546.003 - Windows Management Instrumentation Event Subscription|T1546.003: Windows Management Instrumentation Event Subscription]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent credential overlap across systems of administrator and privileged accounts.(Citation: FireEye WMI 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8e5b5ae-85ca-48da-b3a0-36da1162034d`.
