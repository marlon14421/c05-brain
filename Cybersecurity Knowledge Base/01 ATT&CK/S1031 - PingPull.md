---
type: "Malware"
source: MITRE ATT&CK
id: "S1031"
source_url: "https://attack.mitre.org/software/S1031"
created: "2022-08-09"
modified: "2025-04-16"
---
# S1031: PingPull

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1031  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[PingPull](https://attack.mitre.org/software/S1031) is a remote access Trojan (RAT) written in Visual C++ that has been used by [GALLIUM](https://attack.mitre.org/groups/G0093) since at least June 2022. [PingPull](https://attack.mitre.org/software/S1031) has been used to target telecommunications companies, financial institutions, and government entities in Afghanistan, Australia, Belgium, Cambodia, Malaysia, Mozambique, the Philippines, Russia, and Vietnam.(Citation: Unit 42 PingPull Jun 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1031](https://attack.mitre.org/software/S1031)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
