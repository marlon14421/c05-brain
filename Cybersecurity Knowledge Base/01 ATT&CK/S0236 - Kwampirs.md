---
type: "Malware"
source: MITRE ATT&CK
id: "S0236"
source_url: "https://attack.mitre.org/software/S0236"
created: "2018-10-17"
modified: "2024-04-11"
---
# S0236: Kwampirs

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0236  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Kwampirs](https://attack.mitre.org/software/S0236) is a backdoor Trojan used by [Orangeworm](https://attack.mitre.org/groups/G0071). [Kwampirs](https://attack.mitre.org/software/S0236) has been found on machines which had software installed for the use and control of high-tech imaging devices such as X-Ray and MRI machines.(Citation: Symantec Orangeworm April 2018) [Kwampirs](https://attack.mitre.org/software/S0236) has multiple technical overlaps with [Shamoon](https://attack.mitre.org/software/S0140) based on reverse engineering analysis.(Citation: Cylera Kwampirs 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0236](https://attack.mitre.org/software/S0236)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
