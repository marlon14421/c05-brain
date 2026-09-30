---
type: "Malware"
source: MITRE ATT&CK
id: "S9007"
source_url: "https://attack.mitre.org/software/S9007"
created: "2026-04-08"
modified: "2026-04-23"
---
# S9007: HTTPTroy

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9007  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[HTTPTroy](https://attack.mitre.org/software/S9007) is a highly obfuscated backdoor that facilitates collection, command and control, defense evasion and exfiltration. [HTTPTroy](https://attack.mitre.org/software/S9007) was first reported in October 2025. [HTTPTroy](https://attack.mitre.org/software/S9007) has been observed in operations attributed to DPRK-affiliated threat actors, including [Kimsuky](https://attack.mitre.org/groups/G0094). [HTTPTroy](https://attack.mitre.org/software/S9007) has been delivered to victims through a separate loader leveraged by [Kimsuky](https://attack.mitre.org/groups/G0094).(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9007](https://attack.mitre.org/software/S9007)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
