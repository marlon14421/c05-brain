---
type: "Malware"
source: MITRE ATT&CK
id: "S1228"
source_url: "https://attack.mitre.org/software/S1228"
created: "2025-08-04"
modified: "2026-05-12"
---
# S1228: PUBLOAD

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1228  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[PUBLOAD](https://attack.mitre.org/software/S1228) is a stager malware that has been observed installing itself in existing directories such as `C:\Users\Public` or creating new directories to stage the malware and its components.(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload) [PUBLOAD](https://attack.mitre.org/software/S1228) malware collects details of the victim host, establishes persistence, encrypts victim details using RC4 and communicates victim details back to C2. [PUBLOAD](https://attack.mitre.org/software/S1228) malware has previously been leveraged by China-affiliated actors identified as [Mustang Panda](https://attack.mitre.org/groups/G0129). [PUBLOAD](https://attack.mitre.org/software/S1228) is also known as “NoFive” and some public reporting identifies the loader component as [CLAIMLOADER](https://attack.mitre.org/software/S1236).(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1228](https://attack.mitre.org/software/S1228)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
