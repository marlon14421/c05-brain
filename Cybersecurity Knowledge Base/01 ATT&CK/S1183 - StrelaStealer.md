---
type: "Malware"
source: MITRE ATT&CK
id: "S1183"
source_url: "https://attack.mitre.org/software/S1183"
created: "2024-12-31"
modified: "2025-03-10"
---
# S1183: StrelaStealer

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1183  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[StrelaStealer](https://attack.mitre.org/software/S1183) is an information stealer malware variant first identified in November 2022 and active through late 2024. [StrelaStealer](https://attack.mitre.org/software/S1183) focuses on the automated identification, collection, and exfiltration of email credentials from email clients such as Outlook and Thunderbird.(Citation: DCSO StrelaStealer 2022)(Citation: PaloAlto StrelaStealer 2024)(Citation: Fortgale StrelaStealer 2023)(Citation: IBM StrelaStealer 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1183](https://attack.mitre.org/software/S1183)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
