---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "S0677"
stix_relationship_id: "relationship--ff916215-e7dc-410a-919c-83a00eb95dc1"
---
# Relationship 4332: G1053 — uses → S0677

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0677 - AADInternals|S0677: AADInternals]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) used the PowerShell module [AADInternals](https://attack.mitre.org/software/S0677) to create a back door within the victim tenant, thus allowing for the impersonation of any user in the organization and bypassing MFA to sign in to any application to include Office 365.(Citation: Microsoft Storm-501 Sabbath Ransomware Embargo September 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff916215-e7dc-410a-919c-83a00eb95dc1`.
