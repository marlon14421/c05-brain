---
type: "Malware"
source: MITRE ATT&CK
id: "S1041"
source_url: "https://attack.mitre.org/software/S1041"
created: "2022-09-21"
modified: "2024-04-11"
---
# S1041: Chinoxy

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1041  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Chinoxy](https://attack.mitre.org/software/S1041) is a backdoor that has been used since at least November 2018, during the [FunnyDream](https://attack.mitre.org/campaigns/C0007) campaign, to gain persistence and drop additional payloads. According to security researchers, [Chinoxy](https://attack.mitre.org/software/S1041) has been used by Chinese-speaking threat actors.(Citation: Bitdefender FunnyDream Campaign November 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1041](https://attack.mitre.org/software/S1041)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
