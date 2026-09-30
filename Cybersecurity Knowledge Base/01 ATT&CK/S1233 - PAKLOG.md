---
type: "Malware"
source: MITRE ATT&CK
id: "S1233"
source_url: "https://attack.mitre.org/software/S1233"
created: "2025-09-12"
modified: "2025-10-21"
---
# S1233: PAKLOG

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1233  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[PAKLOG](https://attack.mitre.org/software/S1233) is a keylogger known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) and was first observed utilized in 2024. [PAKLOG](https://attack.mitre.org/software/S1233) is deployed via a RAR archive (e.g., key.rar), which contains two files: a signed, legitimate binary (PACLOUD.exe) and the malicious [PAKLOG](https://attack.mitre.org/software/S1233) DLL (pa_lang2.dll). The PACLOUD.exe binary is used to side-load the [PAKLOG](https://attack.mitre.org/software/S1233) DLL which starts with the keylogger functionality.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1233](https://attack.mitre.org/software/S1233)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
