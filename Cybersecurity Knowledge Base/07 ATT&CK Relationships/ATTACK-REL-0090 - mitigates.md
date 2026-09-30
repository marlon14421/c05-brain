---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1556.007"
stix_relationship_id: "relationship--a7c79cef-cd50-4106-a78d-fc56cb2da51a"
---
# Relationship 0090: M1026 — mitigates → T1556.007

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1556.007 - Hybrid Identity|T1556.007: Hybrid Identity]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit on-premises accounts with access to the hybrid identity solution in place. For example, limit Entra ID Global Administrator accounts to only those required, and ensure that these are dedicated cloud-only accounts rather than hybrid ones.(Citation: MagicWeb)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a7c79cef-cd50-4106-a78d-fc56cb2da51a`.
