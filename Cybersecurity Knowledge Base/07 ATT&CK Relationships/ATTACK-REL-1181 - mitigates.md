---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1015"
target_object: "T1606.002"
stix_relationship_id: "relationship--3278a7a8-bf61-45bc-9553-872f222f699d"
---
# Relationship 1181: M1015 — mitigates → T1606.002

**Source object:** [[01 ATT&CK/M1015 - Active Directory Configuration|M1015: Active Directory Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1606.002 - SAML Tokens|T1606.002: SAML Tokens]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

For containing the impact of a previously forged SAML token, rotate the token-signing AD FS certificate in rapid succession twice, which will invalidate any tokens generated using the previous certificate.(Citation: Mandiant Defend UNC2452 White Paper)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3278a7a8-bf61-45bc-9553-872f222f699d`.
