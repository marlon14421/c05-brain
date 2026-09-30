---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1078.004"
stix_relationship_id: "relationship--4dbb52bd-9ecf-4c61-91b2-9787860f737c"
---
# Relationship 1343: M1026 — mitigates → T1078.004

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Review privileged cloud account permission levels routinely to look for those that could allow an adversary to gain wide access, such as Global Administrator and Privileged Role Administrator in Azure AD.(Citation: TechNet Credential Theft)(Citation: TechNet Least Privilege)(Citation: Microsoft Azure security baseline for Azure Active Directory) These reviews should also check if new privileged cloud accounts have been created that were not authorized. For example, in Azure AD environments configure alerts to notify when accounts have gone many days without using privileged roles, as these roles may be able to be removed.(Citation: Microsoft Security Alerts for Azure AD Roles) Consider using temporary, just-in-time (JIT) privileged access to Azure AD resources rather than permanently assigning privileged roles.(Citation: Microsoft Azure security baseline for Azure Active Directory)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4dbb52bd-9ecf-4c61-91b2-9787860f737c`.
