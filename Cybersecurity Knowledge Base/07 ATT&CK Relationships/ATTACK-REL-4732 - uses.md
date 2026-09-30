---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0024"
target_object: "T1552.004"
stix_relationship_id: "relationship--6934c7b5-96ce-4265-aea3-7eae018d7f3c"
---
# Relationship 4732: C0024 — uses → T1552.004

**Source object:** [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024: SolarWinds Compromise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.004 - Private Keys|T1552.004: Private Keys]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024), [APT29](https://attack.mitre.org/groups/G0016) obtained PKI keys, certificate files, and the private encryption key from an Active Directory Federation Services (AD FS) container to decrypt corresponding SAML signing certificates.(Citation: Microsoft 365 Defender Solorigate)(Citation: Cybersecurity Advisory SVR TTP May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6934c7b5-96ce-4265-aea3-7eae018d7f3c`.
