---
type: "Malware"
source: MITRE ATT&CK
id: "S1143"
source_url: "https://attack.mitre.org/software/S1143"
created: "2024-06-27"
modified: "2024-06-27"
---
# S1143: LunarLoader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1143  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[LunarLoader](https://attack.mitre.org/software/S1143) is the loader component for the [LunarWeb](https://attack.mitre.org/software/S1141) and [LunarMail](https://attack.mitre.org/software/S1142) backdoors that has been used by [Turla](https://attack.mitre.org/groups/G0010) since at least 2020 including against a European ministry of foreign affairs (MFA). [LunarLoader](https://attack.mitre.org/software/S1143) has been observed as a standalone and as a part of trojanized open-source software such as AdmPwd.(Citation: ESET Turla Lunar toolset May 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1143](https://attack.mitre.org/software/S1143)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
