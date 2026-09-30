---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1566.001"
stix_relationship_id: "relationship--9d239fc5-5d40-4991-ae41-761686ab43a2"
---
# Relationship 7576: G0129 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has used spearphishing attachments to deliver initial access payloads.(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: CSIRT CTI MUSTANG PANDA PUBLOAD TONESHELL JAN 2024)(Citation: Lab52 MUSTANG PANDA PUBLOAD MAY 2023)(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: Google TAG Ukraine Threat Landscape March 2022)(Citation: Recorded Future REDDELTA July 2020)(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024)(Citation: Proofpoint TA416 November 2020) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also delivered archive files such as RAR and ZIP files containing legitimate EXEs and malicious DLLs.(Citation: Lab52 MUSTANG PANDA PUBLOAD MAY 2023)(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d239fc5-5d40-4991-ae41-761686ab43a2`.
