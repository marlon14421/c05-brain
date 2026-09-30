---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1566.001"
stix_relationship_id: "relationship--b9f1dec0-f9b8-4cc3-a26c-5fc819f603a0"
---
# Relationship 9676: G0094 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used emails containing Word, Excel and/or HWP (Hangul Word Processor) documents in their spearphishing campaigns.(Citation: Zdnet Kimsuky Dec 2018)(Citation: Securelist Kimsuky Sept 2013)(Citation: ThreatConnect Kimsuky September 2020)(Citation: VirusBulletin Kimsuky October 2019)(Citation: Cybereason Kimsuky November 2020)(Citation: Malwarebytes Kimsuky June 2021)(Citation: Talos Kimsuky Nov 2021)(Citation: KISA Operation Muzabi) [Kimsuky](https://attack.mitre.org/groups/G0094) has also distributed emails with attached compressed zip files that contained malicious .LNK files masquerading as legitimate files.(Citation: Securonix Kimsuky February 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has delivered tailored PDF documents that contain malicious links.(Citation: NaumaanProofpoint_GlobalClickFix_April2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b9f1dec0-f9b8-4cc3-a26c-5fc819f603a0`.
