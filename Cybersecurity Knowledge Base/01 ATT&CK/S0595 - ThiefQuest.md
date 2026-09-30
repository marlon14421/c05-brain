---
type: "Malware"
source: MITRE ATT&CK
id: "S0595"
source_url: "https://attack.mitre.org/software/S0595"
created: "2021-03-19"
modified: "2025-04-16"
---
# S0595: ThiefQuest

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0595  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

[ThiefQuest](https://attack.mitre.org/software/S0595) is a virus, data stealer, and wiper that presents itself as ransomware targeting macOS systems. [ThiefQuest](https://attack.mitre.org/software/S0595) was first seen in 2020 distributed via trojanized pirated versions of popular macOS software on Russian forums sharing torrent links.(Citation: Reed thiefquest fake ransom) Even though [ThiefQuest](https://attack.mitre.org/software/S0595) presents itself as ransomware, since the dynamically generated encryption key is never sent to the attacker it may be more appropriately thought of as a form of wiper malware.(Citation: wardle evilquest partii)(Citation: reed thiefquest ransomware analysis)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0595](https://attack.mitre.org/software/S0595)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
