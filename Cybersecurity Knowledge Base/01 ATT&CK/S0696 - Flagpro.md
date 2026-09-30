---
type: "Malware"
source: MITRE ATT&CK
id: "S0696"
source_url: "https://attack.mitre.org/software/S0696"
created: "2022-03-25"
modified: "2025-04-25"
---
# S0696: Flagpro

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0696  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Flagpro](https://attack.mitre.org/software/S0696) is a Windows-based, first-stage downloader that has been used by [BlackTech](https://attack.mitre.org/groups/G0098) since at least October 2020. It has primarily been used against defense, media, and communications companies in Japan.(Citation: NTT Security Flagpro new December 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0696](https://attack.mitre.org/software/S0696)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
