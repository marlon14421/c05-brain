---
type: "Malware"
source: MITRE ATT&CK
id: "S1052"
source_url: "https://attack.mitre.org/software/S1052"
created: "2022-12-20"
modified: "2024-04-11"
---
# S1052: DEADEYE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1052  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[DEADEYE](https://attack.mitre.org/software/S1052) is a malware launcher that has been used by [APT41](https://attack.mitre.org/groups/G0096) since at least May 2021. [DEADEYE](https://attack.mitre.org/software/S1052) has variants that can either embed a payload inside a compiled binary (DEADEYE.EMBED) or append it to the end of a file (DEADEYE.APPEND).(Citation: Mandiant APT41)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1052](https://attack.mitre.org/software/S1052)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
