---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0069"
target_object: "T1204.002"
stix_relationship_id: "relationship--d06420fb-1c4d-4a4e-b18e-4c0750310606"
---
# Relationship 8628: G0069 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0069 - MuddyWater|G0069: MuddyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MuddyWater](https://attack.mitre.org/groups/G0069) has attempted to get users to open malicious PDF attachment and to enable macros and launch malicious Microsoft Word documents delivered via spearphishing emails.(Citation: Unit 42 MuddyWater Nov 2017)(Citation: FireEye MuddyWater Mar 2018)(Citation: Securelist MuddyWater Oct 2018)(Citation: Talos MuddyWater May 2019)(Citation: ClearSky MuddyWater June 2019)(Citation: Reaqta MuddyWater November 2017)(Citation: Anomali Static Kitten February 2021)(Citation: Trend Micro Muddy Water March 2021)(Citation: DHS CISA AA22-055A MuddyWater February 2022)(Citation: Talos MuddyWater Jan 2022)(Citation: Proofpoint TA450 Phishing March 2024) Additionally, [MuddyWater](https://attack.mitre.org/groups/G0069) has used a Word document with a malicious Visual Basic for Applications (VBA) macro; when enabled, the CertificationKit.ini payload is constructed and executed.(Citation: CloudSEK_RustyWater_Jan2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d06420fb-1c4d-4a4e-b18e-4c0750310606`.
