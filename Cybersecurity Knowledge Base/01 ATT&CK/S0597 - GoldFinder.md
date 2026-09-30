---
type: "Malware"
source: MITRE ATT&CK
id: "S0597"
source_url: "https://attack.mitre.org/software/S0597"
created: "2021-03-26"
modified: "2025-04-16"
---
# S0597: GoldFinder

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0597  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[GoldFinder](https://attack.mitre.org/software/S0597) is a custom HTTP tracer tool written in Go that logs the route a packet takes between a compromised network and a C2 server. It can be used to inform threat actors of potential points of discovery or logging of their actions, including C2 related to other malware. [GoldFinder](https://attack.mitre.org/software/S0597) was discovered in early 2021 during an investigation into the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024) by [APT29](https://attack.mitre.org/groups/G0016).(Citation: MSTIC NOBELIUM Mar 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0597](https://attack.mitre.org/software/S0597)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
