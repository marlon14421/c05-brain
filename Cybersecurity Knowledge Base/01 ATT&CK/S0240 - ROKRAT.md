---
type: "Malware"
source: MITRE ATT&CK
id: "S0240"
source_url: "https://attack.mitre.org/software/S0240"
created: "2018-10-17"
modified: "2025-04-25"
---
# S0240: ROKRAT

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0240  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[ROKRAT](https://attack.mitre.org/software/S0240) is a cloud-based remote access tool (RAT) used by [APT37](https://attack.mitre.org/groups/G0067) to target victims in South Korea. [APT37](https://attack.mitre.org/groups/G0067) has used ROKRAT during several campaigns from 2016 through 2021.(Citation: Talos ROKRAT)(Citation: Talos Group123)(Citation: Volexity InkySquid RokRAT August 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0240](https://attack.mitre.org/software/S0240)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
