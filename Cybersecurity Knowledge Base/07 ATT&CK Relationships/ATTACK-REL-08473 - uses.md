---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1059.005"
stix_relationship_id: "relationship--ee4701f6-e4a5-41c8-ab72-118aead20a76"
---
# Relationship 8473: G0094 — uses → T1059.005

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used Visual Basic to download malicious payloads.(Citation: ThreatConnect Kimsuky September 2020)(Citation: VirusBulletin Kimsuky October 2019)(Citation: Crowdstrike GTR2020 Mar 2020)(Citation: Talos Kimsuky Nov 2021)(Citation: Aryaka Kimsuky July 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has also used malicious VBA macros within maldocs disguised as forms that trigger when a victim types any content into the lure.(Citation: Talos Kimsuky Nov 2021) [Kimsuky](https://attack.mitre.org/groups/G0094) has also leveraged VBScript (VBS) scripts to execute temp.vbs every 19 minutes using a scheduled task to run [QuasarRAT](https://attack.mitre.org/software/S0262).(Citation: NaumaanProofpoint_GlobalClickFix_April2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ee4701f6-e4a5-41c8-ab72-118aead20a76`.
