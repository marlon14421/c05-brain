---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1098.005"
stix_relationship_id: "relationship--56f2efc6-fb22-47f9-a86f-db5c69224936"
---
# Relationship 0439: M1032 — mitigates → T1098.005

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1098.005 - Device Registration|T1098.005: Device Registration]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Require multi-factor authentication to register devices in Entra ID.(Citation: Microsoft - Device Registration) Configure multi-factor authentication systems to disallow enrolling new devices for inactive accounts.(Citation: CISA MFA PrintNightmare) When first enrolling MFA, use conditional access policies to restrict device enrollment to trusted locations or devices, and consider using temporary access passes as an initial MFA solution to enroll a device.(Citation: Mandiant APT29 Microsoft 365 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56f2efc6-fb22-47f9-a86f-db5c69224936`.
