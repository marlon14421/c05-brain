---
type: "Malware"
source: MITRE ATT&CK
id: "S0533"
source_url: "https://attack.mitre.org/software/S0533"
created: "2020-11-16"
modified: "2025-10-21"
---
# S0533: SLOTHFULMEDIA

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0533  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) is a remote access Trojan written in C++ that has been used by an unidentified "sophisticated cyber actor" since at least January 2017.(Citation: CISA MAR SLOTHFULMEDIA October 2020)(Citation: Costin Raiu IAmTheKing October 2020) It has been used to target government organizations, defense contractors, universities, and energy companies in Russia, India, Kazakhstan, Kyrgyzstan, Malaysia, Ukraine, and Eastern Europe.(Citation: USCYBERCOM SLOTHFULMEDIA October 2020)(Citation: Kaspersky IAmTheKing October 2020) In October 2020, Kaspersky Labs assessed [SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) is part of an activity cluster it refers to as "IAmTheKing".(Citation: Kaspersky IAmTheKing October 2020) ESET also noted code similarity between [SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) and droppers used by a group it refers to as "PowerPool".(Citation: ESET PowerPool Code October 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0533](https://attack.mitre.org/software/S0533)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
