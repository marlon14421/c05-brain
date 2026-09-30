---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1204.002"
stix_relationship_id: "relationship--e122c13d-078d-4404-b2a0-e0e2341dbd2e"
---
# Relationship 9729: G0129 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has sent malicious files requiring direct victim interaction to execute.(Citation: Anomali MUSTANG PANDA October 2019)(Citation: CSIRT CTI MUSTANG PANDA PUBLOAD TONESHELL JAN 2024)(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: Avira Mustang Panda January 2020)(Citation: Google TAG Ukraine Threat Landscape March 2022)(Citation: Recorded Future REDDELTA July 2020)(Citation: Crowdstrike MUSTANG PANDA June 2018)(Citation: Proofpoint TA416 Europe March 2022)(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also leveraged executable files that display decoy documents to the victim to provide a resemblance of legitimacy with customized themes related to the victim.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: Lab52 MUSTANG PANDA PUBLOAD MAY 2023)(Citation: EclecticIQ Mustang Panda PlugX)(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024)(Citation: Trend Micro Mustang Panda Earth Preta Toneshell February 2025)(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload)(Citation: Unit42 Bookworm Nov2015)(Citation: Palo Alto Networks, Unit 42)(Citation: Sophos PlugX September 2022)(Citation: Sophos Mustang Panda PLUGX)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e122c13d-078d-4404-b2a0-e0e2341dbd2e`.
