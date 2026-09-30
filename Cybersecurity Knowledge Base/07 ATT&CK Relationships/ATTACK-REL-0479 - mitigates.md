---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1133"
stix_relationship_id: "relationship--e23d57b4-5bc4-4d06-9084-9c99464c4af8"
---
# Relationship 0479: M1032 — mitigates → T1133

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1133 - External Remote Services|T1133: External Remote Services]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use strong two-factor or multi-factor authentication for remote service accounts to mitigate an adversary's ability to leverage stolen credentials, but be aware of [Multi-Factor Authentication Interception](https://attack.mitre.org/techniques/T1111) techniques for some two-factor authentication implementations.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e23d57b4-5bc4-4d06-9084-9c99464c4af8`.
