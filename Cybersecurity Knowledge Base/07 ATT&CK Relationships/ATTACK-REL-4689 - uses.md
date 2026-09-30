---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1228"
target_object: "T1082"
stix_relationship_id: "relationship--ff57d2d8-095c-4f9b-bb57-bc0971bb6a8d"
---
# Relationship 4689: S1228 — uses → T1082

**Source object:** [[01 ATT&CK/S1228 - PUBLOAD|S1228: PUBLOAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PUBLOAD](https://attack.mitre.org/software/S1228) has collected and sent system information including volume serial number, computer name, and system uptime to designated C2.(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA) [PUBLOAD](https://attack.mitre.org/software/S1228) has also used several commands executed in sequence via `cmd` in a short interval to gather system information about the infected host including `systeminfo`.(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024) [PUBLOAD](https://attack.mitre.org/software/S1228) has decrypted shellcode that collects the computer name.(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff57d2d8-095c-4f9b-bb57-bc0971bb6a8d`.
