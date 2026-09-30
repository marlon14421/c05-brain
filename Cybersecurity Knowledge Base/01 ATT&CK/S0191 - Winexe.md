---
type: "Tool"
source: MITRE ATT&CK
id: "S0191"
source_url: "https://attack.mitre.org/software/S0191"
created: "2018-04-18"
modified: "2024-09-04"
---
# S0191: Winexe

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Tool  
**ATT&CK ID:** S0191  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[Winexe](https://attack.mitre.org/software/S0191) is a lightweight, open source tool similar to [PsExec](https://attack.mitre.org/software/S0029) designed to allow system administrators to execute commands on remote servers. (Citation: Winexe Github Sept 2013) [Winexe](https://attack.mitre.org/software/S0191) is unique in that it is a GNU/Linux based client. (Citation: Überwachung APT28 Forfiles June 2015)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0191](https://attack.mitre.org/software/S0191)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
