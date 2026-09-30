---
type: "Malware"
source: MITRE ATT&CK
id: "S0518"
source_url: "https://attack.mitre.org/software/S0518"
created: "2020-09-23"
modified: "2025-04-16"
---
# S0518: PolyglotDuke

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0518  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[PolyglotDuke](https://attack.mitre.org/software/S0518) is a downloader that has been used by [APT29](https://attack.mitre.org/groups/G0016) since at least 2013. [PolyglotDuke](https://attack.mitre.org/software/S0518) has been used to drop [MiniDuke](https://attack.mitre.org/software/S0051).(Citation: ESET Dukes October 2019)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0518](https://attack.mitre.org/software/S0518)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
