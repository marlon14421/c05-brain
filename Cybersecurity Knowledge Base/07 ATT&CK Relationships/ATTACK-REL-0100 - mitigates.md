---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1036"
target_object: "T1621"
stix_relationship_id: "relationship--a09cb233-bdff-4d89-bcc3-7fb2108911d0"
---
# Relationship 0100: M1036 — mitigates → T1621

**Source object:** [[01 ATT&CK/M1036 - Account Use Policies|M1036: Account Use Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1621 - Multi-Factor Authentication Request Generation|T1621: Multi-Factor Authentication Request Generation]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enable account restrictions to prevent login attempts, and the subsequent 2FA/MFA service requests, from being initiated from suspicious locations or when the source of the login attempts do not match the location of the 2FA/MFA smart device. Use conditional access policies to block logins from non-compliant devices or from outside defined organization IP ranges.(Citation: Microsoft Common Conditional Access Policies)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a09cb233-bdff-4d89-bcc3-7fb2108911d0`.
