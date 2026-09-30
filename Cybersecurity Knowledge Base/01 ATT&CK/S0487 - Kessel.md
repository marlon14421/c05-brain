---
type: "Malware"
source: MITRE ATT&CK
id: "S0487"
source_url: "https://attack.mitre.org/software/S0487"
created: "2020-07-16"
modified: "2024-04-11"
---
# S0487: Kessel

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0487  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

[Kessel](https://attack.mitre.org/software/S0487) is an advanced version of OpenSSH which acts as a custom backdoor, mainly acting to steal credentials and function as a bot. [Kessel](https://attack.mitre.org/software/S0487) has been active since its C2 domain began resolving in August 2018.(Citation: ESET ForSSHe December 2018)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0487](https://attack.mitre.org/software/S0487)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
