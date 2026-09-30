---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1027"
target_object: "T1558.004"
stix_relationship_id: "relationship--6e751301-3697-4851-b55c-259976891406"
---
# Relationship 0508: M1027 — mitigates → T1558.004

**Source object:** [[01 ATT&CK/M1027 - Password Policies|M1027: Password Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1558.004 - AS-REP Roasting|T1558.004: AS-REP Roasting]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure strong password length (ideally 25+ characters) and complexity for service accounts and that these passwords periodically expire. Also consider using Group Managed Service Accounts or another third party product such as password vaulting. (Citation: AdSecurity Cracking Kerberos Dec 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e751301-3697-4851-b55c-259976891406`.
