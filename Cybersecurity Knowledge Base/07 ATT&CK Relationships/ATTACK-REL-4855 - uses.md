---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1574.001"
stix_relationship_id: "relationship--ac77f5ac-4a6e-4c58-a596-5e9aa6f00ff7"
---
# Relationship 4855: G0129 — uses → T1574.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has used a legitimately signed executable to execute a malicious payload within a DLL file.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Anomali MUSTANG PANDA October 2019)(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: Broadcom)(Citation: EclecticIQ Mustang Panda PlugX)(Citation: Recorded Future REDDELTA July 2020)(Citation: Palo Alto Unit42 STATELY TAURUS TONESHELL September 2023)(Citation: Trend Micro Mustang Panda Earth Preta Toneshell February 2025)(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload)(Citation: Proofpoint TA416 November 2020)(Citation: Unit42 Bookworm Nov2015)(Citation: Sophos PlugX September 2022)(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)(Citation: Zscaler) [Mustang Panda](https://attack.mitre.org/groups/G0129) has abused legitimate executables to side-load malicious DLLs.(Citation: CSIRT CTI MUSTANG PANDA PUBLOAD TONESHELL JAN 2024)(Citation: Lab52 MUSTANG PANDA PUBLOAD MAY 2023)(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: Google Threat Intelligence Group MUSTANG PANDA PLUGX August 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac77f5ac-4a6e-4c58-a596-5e9aa6f00ff7`.
