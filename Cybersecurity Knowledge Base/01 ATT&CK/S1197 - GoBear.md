---
type: "Malware"
source: MITRE ATT&CK
id: "S1197"
source_url: "https://attack.mitre.org/software/S1197"
created: "2025-01-17"
modified: "2025-01-17"
---
# S1197: GoBear

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1197  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[GoBear](https://attack.mitre.org/software/S1197) is a Go-based backdoor that abuses legitimate, stolen certificates for defense evasion purposes. [GoBear](https://attack.mitre.org/software/S1197) is exclusively linked to [Kimsuky](https://attack.mitre.org/groups/G0094) operations.(Citation: S2W Troll Stealer 2024)(Citation: Symantec Troll Stealer 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1197](https://attack.mitre.org/software/S1197)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
