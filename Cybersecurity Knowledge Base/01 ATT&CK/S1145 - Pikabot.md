---
type: "Malware"
source: MITRE ATT&CK
id: "S1145"
source_url: "https://attack.mitre.org/software/S1145"
created: "2024-07-12"
modified: "2024-10-28"
---
# S1145: Pikabot

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1145  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Pikabot](https://attack.mitre.org/software/S1145) is a backdoor used for initial access and follow-on tool deployment active since early 2023. [Pikabot](https://attack.mitre.org/software/S1145) is notable for extensive use of multiple encoding, encryption, and defense evasion mechanisms to evade defenses and avoid analysis. [Pikabot](https://attack.mitre.org/software/S1145) has some overlaps with [QakBot](https://attack.mitre.org/software/S0650), but insufficient evidence exists to definitively link these two malware families. [Pikabot](https://attack.mitre.org/software/S1145) is frequently used to deploy follow on tools such as [Cobalt Strike](https://attack.mitre.org/software/S0154) or ransomware variants.(Citation: Zscaler Pikabot 2023)(Citation: Elastic Pikabot 2024)(Citation: Logpoint Pikabot 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1145](https://attack.mitre.org/software/S1145)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
