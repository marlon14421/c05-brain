---
type: "Malware"
source: MITRE ATT&CK
id: "S1096"
source_url: "https://attack.mitre.org/software/S1096"
created: "2023-12-18"
modified: "2025-04-15"
---
# S1096: Cheerscrypt

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1096  
**Platforms:** Windows, ESXi  
**Tactics:** Not specified

## Source description

[Cheerscrypt](https://attack.mitre.org/software/S1096) is a ransomware that was developed by [Cinnamon Tempest](https://attack.mitre.org/groups/G1021) and has been used in attacks against ESXi and Windows environments since at least 2022. [Cheerscrypt](https://attack.mitre.org/software/S1096) was derived from the leaked [Babuk](https://attack.mitre.org/software/S0638) source code and has infrastructure overlaps with deployments of Night Sky ransomware, which was also derived from [Babuk](https://attack.mitre.org/software/S0638).(Citation: Sygnia Emperor Dragonfly October 2022)(Citation: Trend Micro Cheerscrypt May 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1096](https://attack.mitre.org/software/S1096)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
