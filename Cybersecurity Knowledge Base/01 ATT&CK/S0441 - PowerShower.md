---
type: "Malware"
source: MITRE ATT&CK
id: "S0441"
source_url: "https://attack.mitre.org/software/S0441"
created: "2020-05-08"
modified: "2025-04-25"
---
# S0441: PowerShower

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0441  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[PowerShower](https://attack.mitre.org/software/S0441) is a PowerShell backdoor used by [Inception](https://attack.mitre.org/groups/G0100) for initial reconnaissance and to download and execute second stage payloads.(Citation: Unit 42 Inception November 2018)(Citation: Kaspersky Cloud Atlas August 2019)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0441](https://attack.mitre.org/software/S0441)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
