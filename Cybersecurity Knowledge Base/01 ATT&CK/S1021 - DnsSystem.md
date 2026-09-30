---
type: "Malware"
source: MITRE ATT&CK
id: "S1021"
source_url: "https://attack.mitre.org/software/S1021"
created: "2022-06-24"
modified: "2025-04-16"
---
# S1021: DnsSystem

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1021  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[DnsSystem](https://attack.mitre.org/software/S1021) is a .NET based DNS backdoor, which is a customized version of the open source tool DIG.net, that has been used by [HEXANE](https://attack.mitre.org/groups/G1001) since at least June 2022.(Citation: Zscaler Lyceum DnsSystem June 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1021](https://attack.mitre.org/software/S1021)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
