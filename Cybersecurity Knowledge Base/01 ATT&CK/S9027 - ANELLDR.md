---
type: "Malware"
source: MITRE ATT&CK
id: "S9027"
source_url: "https://attack.mitre.org/software/S9027"
created: "2026-04-19"
modified: "2026-04-24"
---
# S9027: ANELLDR

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9027  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[ANELLDR](https://attack.mitre.org/software/S9027), a loader that has been in use since at least 2018, was designed to decrypt and execute [UPPERCUT](https://attack.mitre.org/software/S0275) in memory. [ANELLDR](https://attack.mitre.org/software/S9027) can use anti-analysis techniques and is known to share code overlap with [HiddenFace](https://attack.mitre.org/software/S9023).(Citation: Trend Micro Earth Kasha Anel NOV 2024)(Citation: ESET MirrorFace 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9027](https://attack.mitre.org/software/S9027)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
