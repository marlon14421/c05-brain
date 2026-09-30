---
type: "Malware"
source: MITRE ATT&CK
id: "S1064"
source_url: "https://attack.mitre.org/software/S1064"
created: "2023-02-10"
modified: "2025-04-16"
---
# S1064: SVCReady

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1064  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SVCReady](https://attack.mitre.org/software/S1064) is a loader that has been used since at least April 2022 in malicious spam campaigns. Security researchers have noted overlaps between [TA551](https://attack.mitre.org/groups/G0127) activity and [SVCReady](https://attack.mitre.org/software/S1064) distribution, including similarities in file names, lure images, and identical grammatical errors.(Citation: HP SVCReady Jun 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1064](https://attack.mitre.org/software/S1064)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
