---
type: "Malware"
source: MITRE ATT&CK
id: "S1235"
source_url: "https://attack.mitre.org/software/S1235"
created: "2025-09-12"
modified: "2025-10-21"
---
# S1235: CorKLOG

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1235  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[CorKLOG](https://attack.mitre.org/software/S1235) is a keylogger known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) and was first observed utilized in 2024. [CorKLOG](https://attack.mitre.org/software/S1235) is delivered through a RAR archive (e.g., src.rar), which contains two files: an executable (lcommute.exe) and the [CorKLOG](https://attack.mitre.org/software/S1235) DLL (mscorsvc.dll). [CorKLOG](https://attack.mitre.org/software/S1235) has established persistence on the system by creating services or with scheduled tasks.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1235](https://attack.mitre.org/software/S1235)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
