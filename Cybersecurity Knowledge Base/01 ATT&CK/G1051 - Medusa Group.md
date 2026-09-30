---
type: "Threat Group"
source: MITRE ATT&CK
id: "G1051"
source_url: "https://attack.mitre.org/groups/G1051"
created: "2025-10-15"
modified: "2026-07-31"
---
# G1051: Medusa Group

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Threat Group  
**ATT&CK ID:** G1051  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has been active since at least 2021 and was initially operated as a closed ransomware group before evolving into a Ransomware-as-a-Service (RaaS) operation. Some reporting indicates that certain attacks may still be conducted directly by the ransomware’s core developers. Public sources have also referred to the group as “Spearwing” or “Medusa Actors.” (Citation: CISA Medusa Group Medusa Ransomware March 2025) (Citation: Broadcom Medusa Ransomware Medusa Group March 2025) [Medusa Group](https://attack.mitre.org/groups/G1051) employs living-off-the-land techniques, frequently leveraging publicly available tools and common remote management software to conduct operations. The group engages in double extortion tactics, exfiltrating data prior to encryption and threatening to publish stolen information if ransom demands are not met. (Citation: Security Scorecard Medusa Ransomware January 2024) For initial access, [Medusa Group](https://attack.mitre.org/groups/G1051) has exploited publicly known vulnerabilities, conducted phishing campaigns, and used credentials or access purchased from Initial Access Brokers (IABs). The group is opportunistic and has targeted a wide range of sectors globally. (Citation: Intel471 Medusa Ransomware May 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: G1051](https://attack.mitre.org/groups/G1051)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
