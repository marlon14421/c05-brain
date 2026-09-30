---
type: "Malware"
source: MITRE ATT&CK
id: "S1137"
source_url: "https://attack.mitre.org/software/S1137"
created: "2024-05-22"
modified: "2024-08-29"
---
# S1137: Moneybird

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1137  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Moneybird](https://attack.mitre.org/software/S1137) is a ransomware variant written in C++ associated with [Agrius](https://attack.mitre.org/groups/G1030) operations. The name "Moneybird" is contained in the malware's ransom note and as strings in the executable.(Citation: CheckPoint Agrius 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1137](https://attack.mitre.org/software/S1137)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
