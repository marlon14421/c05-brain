---
type: "Malware"
source: MITRE ATT&CK
id: "S1196"
source_url: "https://attack.mitre.org/software/S1196"
created: "2025-01-17"
modified: "2025-03-24"
---
# S1196: Troll Stealer

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1196  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Troll Stealer](https://attack.mitre.org/software/S1196) is an information stealer written in Go associated with [Kimsuky](https://attack.mitre.org/groups/G0094) operations. [Troll Stealer](https://attack.mitre.org/software/S1196) has typically been delivered through a dropper disguised as a legitimate security program installation file. [Troll Stealer](https://attack.mitre.org/software/S1196) features code similar to [AppleSeed](https://attack.mitre.org/software/S0622), also uniquely associated with [Kimsuky](https://attack.mitre.org/groups/G0094) operations.(Citation: S2W Troll Stealer 2024)(Citation: Symantec Troll Stealer 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1196](https://attack.mitre.org/software/S1196)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
