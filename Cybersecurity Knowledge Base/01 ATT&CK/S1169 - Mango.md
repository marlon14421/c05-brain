---
type: "Malware"
source: MITRE ATT&CK
id: "S1169"
source_url: "https://attack.mitre.org/software/S1169"
created: "2024-11-25"
modified: "2024-11-25"
---
# S1169: Mango

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1169  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Mango](https://attack.mitre.org/software/S1169) is a first-stage backdoor written in C#/.NET that was used by [OilRig](https://attack.mitre.org/groups/G0049) during the [Juicy Mix](https://attack.mitre.org/campaigns/C0044) campaign. [Mango](https://attack.mitre.org/software/S1169) is the successor to [Solar](https://attack.mitre.org/software/S1166) and includes additional exfiltration capabilities, the use of native APIs, and added detection evasion code.(Citation: ESET OilRig Campaigns Sep 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1169](https://attack.mitre.org/software/S1169)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
