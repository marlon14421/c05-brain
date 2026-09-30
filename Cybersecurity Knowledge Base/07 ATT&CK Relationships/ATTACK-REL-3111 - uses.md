---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1585.002"
stix_relationship_id: "relationship--e9575965-967c-46fc-bfda-9305c29b045c"
---
# Relationship 3111: G1052 — uses → T1585.002

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.002 - Email Accounts|T1585.002: Email Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has created fake email accounts to correspond with social media accounts, fake LinkedIn personas, code repository accounts, and job announcements on development job board services.(Citation: Sentinel One Contagious Interview ClickFix September 2025)(Citation: Recorded Future Contagious Inteview BeaverTail InvisibleFerret OtterCookie February 2025)(Citation: Socket HexEval BeaverTail Contagious Interview June 2025)(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: PaloAlto Unit42 ContagiousInterview BeaverTail InvisibileFerret October 2024) [Contagious Interview](https://attack.mitre.org/groups/G1052) has also utilized fake email accounts with Threat Intelligence vendor services.(Citation: Sentinel One Contagious Interview ClickFix September 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9575965-967c-46fc-bfda-9305c29b045c`.
