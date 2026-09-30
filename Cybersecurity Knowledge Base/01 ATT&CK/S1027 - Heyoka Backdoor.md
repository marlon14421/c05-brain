---
type: "Malware"
source: MITRE ATT&CK
id: "S1027"
source_url: "https://attack.mitre.org/software/S1027"
created: "2022-07-25"
modified: "2024-04-11"
---
# S1027: Heyoka Backdoor

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1027  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Heyoka Backdoor](https://attack.mitre.org/software/S1027) is a custom backdoor--based on the Heyoka open source exfiltration tool--that has been used by [Aoqin Dragon](https://attack.mitre.org/groups/G1007) since at least 2013.(Citation: SentinelOne Aoqin Dragon June 2022)(Citation: Sourceforge Heyoka 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1027](https://attack.mitre.org/software/S1027)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
