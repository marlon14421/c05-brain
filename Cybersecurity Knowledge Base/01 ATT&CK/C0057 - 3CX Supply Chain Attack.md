---
type: "Campaign"
source: MITRE ATT&CK
id: "C0057"
source_url: "https://attack.mitre.org/campaigns/C0057"
created: "2025-08-25"
modified: "2026-07-31"
---
# C0057: 3CX Supply Chain Attack

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0057  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The [3CX Supply Chain Attack](https://attack.mitre.org/campaigns/C0057) was the first publicly reported case of one supply chain compromise triggering another, leading to a cascading, two-stage intrusion. The initial supply chain attack began when a 3CX employee downloaded and executed a trojanized, end-of-life version of the X_Trader trading software from Trading Technologies. This provided UNC4736, a threat cluster associated with [AppleJeus](https://attack.mitre.org/groups/G1049), access to the 3CX environment. From there UNC4736 compromised the Windows and macOS build environments used to distribute the 3CX desktop application to their customers.(Citation: Mandiant 3cx UNC4736 2023) While 3CX serves more than 600,000 customers and 12 million users, only a subset of systems were affected. Subsequent targeting focused on victims in the defense and cryptocurrency sectors, where attackers deployed secondary payloads such as Gopuram for credential theft and persistence.(Citation: Kaspersky 3CX Gopuram 2023) The campaign began in late 2022 and was disrupted after security vendors publicly reported the compromise in March 2023.(Citation: 3cx official statement 2023)(Citation: Krebs 3cx overview 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0057](https://attack.mitre.org/campaigns/C0057)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
