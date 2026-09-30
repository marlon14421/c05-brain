---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0274"
target_object: "T1098"
stix_relationship_id: "relationship--fe56443a-5f0b-4120-9d27-d4d98aae69b8"
---
# Relationship 3483: S0274 — uses → T1098

**Source object:** [[01 ATT&CK/S0274 - Calisto|S0274: Calisto]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098 - Account Manipulation|T1098: Account Manipulation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Calisto](https://attack.mitre.org/software/S0274) adds permissions and remote logins to all users.(Citation: Symantec Calisto July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe56443a-5f0b-4120-9d27-d4d98aae69b8`.
