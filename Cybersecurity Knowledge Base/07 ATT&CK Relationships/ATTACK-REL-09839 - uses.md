---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1204.002"
stix_relationship_id: "relationship--9b9dad4a-c597-4979-9129-7753a7c3b3db"
---
# Relationship 9839: G0046 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) lured victims to double-click on images in the attachments they sent which would then execute the hidden LNK file.(Citation: FireEye FIN7 April 2017)(Citation: eSentire FIN7 July 2021)(Citation: CrowdStrike Carbon Spider August 2021) Additionally, [FIN7](https://attack.mitre.org/groups/G0046) has used malicious Microsoft Word and Excel files and Leo VBS to distribute an updated version of [JSS Loader](https://attack.mitre.org/software/S0648) and to distribute the Harpy backdoor.(Citation: Crowdstrike_CarbonSpider_Part2_Nov2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b9dad4a-c597-4979-9129-7753a7c3b3db`.
