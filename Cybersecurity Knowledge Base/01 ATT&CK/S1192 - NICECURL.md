---
type: "Malware"
source: MITRE ATT&CK
id: "S1192"
source_url: "https://attack.mitre.org/software/S1192"
created: "2025-01-08"
modified: "2025-01-08"
---
# S1192: NICECURL

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1192  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[NICECURL](https://attack.mitre.org/software/S1192) is a VBScript-based backdoor used by [APT42](https://attack.mitre.org/groups/G1044) to download additional modules.(Citation: Mandiant APT42-untangling)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1192](https://attack.mitre.org/software/S1192)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
