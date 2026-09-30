---
type: "Malware"
source: MITRE ATT&CK
id: "S0486"
source_url: "https://attack.mitre.org/software/S0486"
created: "2020-07-16"
modified: "2025-04-25"
---
# S0486: Bonadan

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0486  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

[Bonadan](https://attack.mitre.org/software/S0486) is a malicious version of OpenSSH which acts as a custom backdoor. [Bonadan](https://attack.mitre.org/software/S0486) has been active since at least 2018 and combines a new cryptocurrency-mining module with the same credential-stealing module used by the Onderon family of backdoors.(Citation: ESET ForSSHe December 2018)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0486](https://attack.mitre.org/software/S0486)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
