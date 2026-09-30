---
type: "Malware"
source: MITRE ATT&CK
id: "S1088"
source_url: "https://attack.mitre.org/software/S1088"
created: "2023-09-25"
modified: "2023-10-04"
---
# S1088: Disco

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1088  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Disco](https://attack.mitre.org/software/S1088) is a custom implant that has been used by [MoustachedBouncer](https://attack.mitre.org/groups/G1019) since at least 2020 including in campaigns using targeted malicious content injection for initial access and command and control.(Citation: MoustachedBouncer ESET August 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1088](https://attack.mitre.org/software/S1088)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
