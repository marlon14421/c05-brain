---
type: "Malware"
source: MITRE ATT&CK
id: "S0026"
source_url: "https://attack.mitre.org/software/S0026"
created: "2017-05-31"
modified: "2024-08-28"
---
# S0026: GLOOXMAIL

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0026  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[GLOOXMAIL](https://attack.mitre.org/software/S0026) is malware used by [APT1](https://attack.mitre.org/groups/G0006) that mimics legitimate Jabber/XMPP traffic. (Citation: Mandiant APT1)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0026](https://attack.mitre.org/software/S0026)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
