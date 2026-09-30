---
type: "Malware"
source: MITRE ATT&CK
id: "S0356"
source_url: "https://attack.mitre.org/software/S0356"
created: "2019-01-31"
modified: "2025-10-21"
---
# S0356: KONNI

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0356  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[KONNI](https://attack.mitre.org/software/S0356) is a remote access tool that security researchers assess has been used by North Korean cyber actors since at least 2014. [KONNI](https://attack.mitre.org/software/S0356) has significant code overlap with the [NOKKI](https://attack.mitre.org/software/S0353) malware family, and has been linked to several suspected North Korean campaigns targeting political organizations in Russia, East Asia, Europe and the Middle East; there is some evidence potentially linking [KONNI](https://attack.mitre.org/software/S0356) to [APT37](https://attack.mitre.org/groups/G0067).(Citation: Talos Konni May 2017)(Citation: Unit 42 NOKKI Sept 2018)(Citation: Unit 42 Nokki Oct 2018)(Citation: Medium KONNI Jan 2020)(Citation: Malwarebytes Konni Aug 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0356](https://attack.mitre.org/software/S0356)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
