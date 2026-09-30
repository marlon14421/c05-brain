---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "T1547.001"
stix_relationship_id: "relationship--6ad8e998-041f-491d-8691-4990022248e0"
---
# Relationship 4337: G0096 — uses → T1547.001

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) created and modified startup files for persistence.(Citation: FireEye APT41 Aug 2019)(Citation: Group IB APT 41 June 2021) [APT41](https://attack.mitre.org/groups/G0096) added a registry key in HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Svchost to establish persistence for [Cobalt Strike](https://attack.mitre.org/software/S0154).(Citation: FireEye APT41 March 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6ad8e998-041f-491d-8691-4990022248e0`.
