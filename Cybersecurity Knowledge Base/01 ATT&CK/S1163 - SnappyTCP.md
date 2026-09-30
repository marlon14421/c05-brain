---
type: "Malware"
source: MITRE ATT&CK
id: "S1163"
source_url: "https://attack.mitre.org/software/S1163"
created: "2024-11-20"
modified: "2025-01-07"
---
# S1163: SnappyTCP

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1163  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

[SnappyTCP](https://attack.mitre.org/software/S1163) is a web shell used by [Sea Turtle](https://attack.mitre.org/groups/G1041) between 2021 and 2023 against multiple victims. [SnappyTCP](https://attack.mitre.org/software/S1163) appears to be based on a public GitHub project that has since been removed from the code-sharing site. [SnappyTCP](https://attack.mitre.org/software/S1163) includes a simple reverse TCP shell for Linux and Unix environments with basic command and control capabilities.(Citation: PWC Sea Turtle 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1163](https://attack.mitre.org/software/S1163)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
