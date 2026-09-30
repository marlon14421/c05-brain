---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1566.002"
stix_relationship_id: "relationship--a3a8c9e7-ed71-46c9-aa1f-c609406652b0"
---
# Relationship 0444: M1018 — mitigates → T1566.002

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Azure AD Administrators apply limitations upon the ability for users to grant consent to unfamiliar or unverified third-party applications.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3a8c9e7-ed71-46c9-aa1f-c609406652b0`.
