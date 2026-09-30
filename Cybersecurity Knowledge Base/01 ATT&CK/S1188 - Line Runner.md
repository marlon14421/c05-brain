---
type: "Malware"
source: MITRE ATT&CK
id: "S1188"
source_url: "https://attack.mitre.org/software/S1188"
created: "2025-01-06"
modified: "2025-04-15"
---
# S1188: Line Runner

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1188  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[Line Runner](https://attack.mitre.org/software/S1188) is a persistent backdoor and web shell allowing threat actors to upload and execute arbitrary Lua scripts. [Line Runner](https://attack.mitre.org/software/S1188) is associated with the [ArcaneDoor](https://attack.mitre.org/campaigns/C0046) campaign.(Citation: CCCS ArcaneDoor 2024)(Citation: Cisco ArcaneDoor 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1188](https://attack.mitre.org/software/S1188)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
