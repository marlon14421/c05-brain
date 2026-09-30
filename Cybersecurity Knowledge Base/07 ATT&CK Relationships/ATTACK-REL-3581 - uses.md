---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1032"
target_object: "T1657"
stix_relationship_id: "relationship--0930ad61-cdf2-451f-bdfe-5c644c3a97c8"
---
# Relationship 3581: G1032 — uses → T1657

**Source object:** [[01 ATT&CK/G1032 - INC Ransom|G1032: INC Ransom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1657 - Financial Theft|T1657: Financial Theft]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[INC Ransom](https://attack.mitre.org/groups/G1032) has stolen and encrypted victim's data in order to extort payment for keeping it private or decrypting it.(Citation: Cybereason INC Ransomware November 2023)(Citation: Bleeping Computer INC Ransomware March 2024)(Citation: Secureworks GOLD IONIC April 2024)(Citation: SOCRadar INC Ransom January 2024)(Citation: SentinelOne INC Ransomware)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0930ad61-cdf2-451f-bdfe-5c644c3a97c8`.
