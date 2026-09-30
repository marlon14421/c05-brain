---
type: "Malware"
source: MITRE ATT&CK
id: "S9022"
source_url: "https://attack.mitre.org/software/S9022"
created: "2026-04-17"
modified: "2026-04-24"
---
# S9022: MirrorStealer

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9022  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[MirrorStealer](https://attack.mitre.org/software/S9022) is a credential stealer that has been used by [MirrorFace](https://attack.mitre.org/groups/G1054) since at least 2022 to steal credentials from various applications, including browsers and email clients. [MirrorStealer](https://attack.mitre.org/software/S9022) has been delivered directly into system memory via commands issued by [LODEINFO](https://attack.mitre.org/software/S9020).(Citation: ESET MirrorFace DEC 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9022](https://attack.mitre.org/software/S9022)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
