---
type: "Malware"
source: MITRE ATT&CK
id: "S1073"
source_url: "https://attack.mitre.org/software/S1073"
created: "2023-03-30"
modified: "2025-10-21"
---
# S1073: Royal

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1073  
**Platforms:** Windows, ESXi  
**Tactics:** Not specified

## Source description

[Royal](https://attack.mitre.org/software/S1073) is ransomware that first appeared in early 2022; a version that also targets ESXi servers was later observed in February 2023. [Royal](https://attack.mitre.org/software/S1073) employs partial encryption and multiple threads to evade detection and speed encryption. [Royal](https://attack.mitre.org/software/S1073) has been used in attacks against multiple industries worldwide--including critical infrastructure. Security researchers have identified similarities in the encryption routines and TTPs used in [Royal](https://attack.mitre.org/software/S1073) and [Conti](https://attack.mitre.org/software/S0575) attacks and noted a possible connection between their operators.(Citation: Microsoft Royal ransomware November 2022)(Citation: Cybereason Royal December 2022)(Citation: Kroll Royal Deep Dive February 2023)(Citation: Trend Micro Royal Linux ESXi February 2023)(Citation: CISA Royal AA23-061A March 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1073](https://attack.mitre.org/software/S1073)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
