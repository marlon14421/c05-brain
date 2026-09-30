---
type: "Malware"
source: MITRE ATT&CK
id: "S1227"
source_url: "https://attack.mitre.org/software/S1227"
created: "2025-07-21"
modified: "2025-10-21"
---
# S1227: StarProxy

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1227  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[StarProxy](https://attack.mitre.org/software/S1227) is custom malware used by [Mustang Panda](https://attack.mitre.org/groups/G0129) as a post-compromise tool, to enable proxying of traffic between the infected machine and other machines on the same network. (Citation: Zscaler)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1227](https://attack.mitre.org/software/S1227)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
