---
type: "Malware"
source: MITRE ATT&CK
id: "S1170"
source_url: "https://attack.mitre.org/software/S1170"
created: "2024-11-26"
modified: "2024-11-27"
---
# S1170: ODAgent

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1170  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[ODAgent](https://attack.mitre.org/software/S1170) is a C#/.NET downloader that has been used by [OilRig](https://attack.mitre.org/groups/G0049) since at least 2022 including against target organizations in Israel to download and execute payloads and to exfiltrate staged files.(Citation: ESET OilRig Downloaders DEC 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1170](https://attack.mitre.org/software/S1170)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
