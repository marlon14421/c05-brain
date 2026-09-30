---
type: "Malware"
source: MITRE ATT&CK
id: "S1016"
source_url: "https://attack.mitre.org/software/S1016"
created: "2022-05-06"
modified: "2025-10-21"
---
# S1016: MacMa

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1016  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

[MacMa](https://attack.mitre.org/software/S1016) is a macOS-based backdoor with a large set of functionalities to control and exfiltrate files from a compromised computer. [MacMa](https://attack.mitre.org/software/S1016) has been observed in the wild since November 2021.(Citation: ESET DazzleSpy Jan 2022) [MacMa](https://attack.mitre.org/software/S1016) shares command and control and unique libraries with [MgBot](https://attack.mitre.org/software/S1146) and [Nightdoor](https://attack.mitre.org/software/S1147), indicating a relationship with the [Daggerfly](https://attack.mitre.org/groups/G1034) threat actor.(Citation: Symantec Daggerfly 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1016](https://attack.mitre.org/software/S1016)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
