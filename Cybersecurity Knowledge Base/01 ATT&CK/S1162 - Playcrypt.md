---
type: "Malware"
source: MITRE ATT&CK
id: "S1162"
source_url: "https://attack.mitre.org/software/S1162"
created: "2024-09-25"
modified: "2024-10-02"
---
# S1162: Playcrypt

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1162  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Playcrypt](https://attack.mitre.org/software/S1162) is a ransomware that has been used by [Play](https://attack.mitre.org/groups/G1040) since at least 2022 in attacks against against the business, government, critical infrastructure, healthcare, and media sectors in North America, South America, and Europe. [Playcrypt](https://attack.mitre.org/software/S1162) derives its name from adding the .play extension to encrypted files and has overlap with tactics and tools associated with Hive and Nokoyawa ransomware and infrastructure associated with Quantum ransomware.(Citation: Microsoft PlayCrypt August 2022)(Citation: CISA Play Ransomware Advisory December 2023)(Citation: Trend Micro Ransomware Spotlight Play July 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1162](https://attack.mitre.org/software/S1162)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
