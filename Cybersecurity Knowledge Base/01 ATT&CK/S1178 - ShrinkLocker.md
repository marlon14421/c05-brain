---
type: "Malware"
source: MITRE ATT&CK
id: "S1178"
source_url: "https://attack.mitre.org/software/S1178"
created: "2024-12-07"
modified: "2026-05-12"
---
# S1178: ShrinkLocker

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1178  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[ShrinkLocker](https://attack.mitre.org/software/S1178) is a VBS-based malicious script that leverages the legitimate Bitlocker application to encrypt files on victim systems for ransom. [ShrinkLocker](https://attack.mitre.org/software/S1178) functions by using Bitlocker to encrypt files, then renames impacted drives to the adversary’s contact email address to facilitate communication for the ransom payment.(Citation: Kaspersky ShrinkLocker 2024)(Citation: Splunk ShrinkLocker 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1178](https://attack.mitre.org/software/S1178)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
