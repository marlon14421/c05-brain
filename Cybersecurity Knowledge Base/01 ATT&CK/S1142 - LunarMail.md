---
type: "Malware"
source: MITRE ATT&CK
id: "S1142"
source_url: "https://attack.mitre.org/software/S1142"
created: "2024-06-26"
modified: "2024-08-16"
---
# S1142: LunarMail

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1142  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[LunarMail](https://attack.mitre.org/software/S1142) is a backdoor that has been used by [Turla](https://attack.mitre.org/groups/G0010) since at least 2020 including in a compromise of a European ministry of foreign affairs (MFA) in conjunction with [LunarLoader](https://attack.mitre.org/software/S1143) and [LunarWeb](https://attack.mitre.org/software/S1141). [LunarMail](https://attack.mitre.org/software/S1142) is designed to be deployed on workstations and can use email messages and [Steganography](https://attack.mitre.org/techniques/T1001/002) in command and control.(Citation: ESET Turla Lunar toolset May 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1142](https://attack.mitre.org/software/S1142)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
