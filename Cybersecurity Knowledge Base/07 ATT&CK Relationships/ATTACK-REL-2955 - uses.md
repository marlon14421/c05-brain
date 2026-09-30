---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1555.005"
stix_relationship_id: "relationship--d474431a-8b2b-4e17-9cbf-e0b28eb00d1a"
---
# Relationship 2955: G1015 — uses → T1555.005

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.005 - Password Managers|T1555.005: Password Managers]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) has searched for credentials in password vaults and Privileged Access Management (PAM) solutions including HashiCorp Vault.(Citation: Mandiant UNC3944 May 2025)(Citation: Mandiant VMware vSphere JUL 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d474431a-8b2b-4e17-9cbf-e0b28eb00d1a`.
