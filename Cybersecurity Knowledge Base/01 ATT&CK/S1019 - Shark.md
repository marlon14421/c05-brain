---
type: "Malware"
source: MITRE ATT&CK
id: "S1019"
source_url: "https://attack.mitre.org/software/S1019"
created: "2022-06-10"
modified: "2024-04-11"
---
# S1019: Shark

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1019  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Shark](https://attack.mitre.org/software/S1019) is a backdoor malware written in C# and .NET that is an updated version of [Milan](https://attack.mitre.org/software/S1015); it has been used by [HEXANE](https://attack.mitre.org/groups/G1001) since at least July 2021.(Citation: ClearSky Siamesekitten August 2021)(Citation: Accenture Lyceum Targets November 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1019](https://attack.mitre.org/software/S1019)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
