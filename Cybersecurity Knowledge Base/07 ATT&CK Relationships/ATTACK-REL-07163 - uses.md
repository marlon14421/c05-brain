---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0092"
target_object: "T1204.002"
stix_relationship_id: "relationship--49d6508c-f350-4376-ba32-f64693d7fd10"
---
# Relationship 7163: G0092 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0092 - TA505|G0092: TA505]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA505](https://attack.mitre.org/groups/G0092) has used lures to get users to enable content in malicious attachments and execute malicious files contained in archives. For example, [TA505](https://attack.mitre.org/groups/G0092) makes their malware look like legitimate Microsoft Word documents, .pdf and/or .lnk files. (Citation: Proofpoint TA505 Sep 2017)(Citation: Proofpoint TA505 June 2018)(Citation: Proofpoint TA505 Jan 2019)(Citation: Cybereason TA505 April 2019)(Citation: ProofPoint SettingContent-ms July 2018)(Citation: Proofpoint TA505 Mar 2018)(Citation: Trend Micro TA505 June 2019)(Citation: Proofpoint TA505 October 2019)(Citation: IBM TA505 April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49d6508c-f350-4376-ba32-f64693d7fd10`.
