---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1583.006"
stix_relationship_id: "relationship--0c98c9a9-a0e4-4f8f-b444-4ba7c3bd38a5"
---
# Relationship 4203: G1052 — uses → T1583.006

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.006 - Web Services|T1583.006: Web Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has used web services such as Dropbox to receive stolen data and Google Drive, Firebase, GitHub, and Telegram to disseminate files.(Citation: Sekoia ClickFake 2025)(Citation: Recorded Future Contagious Inteview BeaverTail InvisibleFerret OtterCookie February 2025) [Contagious Interview](https://attack.mitre.org/groups/G1052) has also used a cloud platform such as Vercel for C2 operations leveraging malicious web applications and static pages.(Citation: Socket Contagious Interview NPM April 2025)(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)(Citation: Socket HexEval BeaverTail Contagious Interview June 2025) [Contagious Interview](https://attack.mitre.org/groups/G1052) has also used Slack to coordinate their activities.(Citation: Sentinel One Contagious Interview ClickFix September 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c98c9a9-a0e4-4f8f-b444-4ba7c3bd38a5`.
