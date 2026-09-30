---
type: "Malware"
source: MITRE ATT&CK
id: "S1023"
source_url: "https://attack.mitre.org/software/S1023"
created: "2022-07-07"
modified: "2025-04-16"
---
# S1023: CreepyDrive

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1023  
**Platforms:** Windows, Office Suite  
**Tactics:** Not specified

## Source description

[CreepyDrive](https://attack.mitre.org/software/S1023) is a custom implant has been used by [POLONIUM](https://attack.mitre.org/groups/G1005) since at least early 2022 for C2 with and exfiltration to actor-controlled OneDrive accounts.(Citation: Microsoft POLONIUM June 2022) [POLONIUM](https://attack.mitre.org/groups/G1005) has used a similar implant called CreepyBox that relies on actor-controlled DropBox accounts.(Citation: Microsoft POLONIUM June 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1023](https://attack.mitre.org/software/S1023)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
