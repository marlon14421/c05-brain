---
type: "Malware"
source: MITRE ATT&CK
id: "S1015"
source_url: "https://attack.mitre.org/software/S1015"
created: "2022-06-06"
modified: "2024-04-11"
---
# S1015: Milan

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1015  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Milan](https://attack.mitre.org/software/S1015) is a backdoor implant based on [DanBot](https://attack.mitre.org/software/S1014) that was written in Visual C++ and .NET. [Milan](https://attack.mitre.org/software/S1015) has been used by [HEXANE](https://attack.mitre.org/groups/G1001) since at least June 2020.(Citation: ClearSky Siamesekitten August 2021)(Citation: Kaspersky Lyceum October 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1015](https://attack.mitre.org/software/S1015)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
