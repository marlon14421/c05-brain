---
type: "Malware"
source: MITRE ATT&CK
id: "S1042"
source_url: "https://attack.mitre.org/software/S1042"
created: "2022-09-21"
modified: "2025-04-16"
---
# S1042: SUGARDUMP

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1042  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SUGARDUMP](https://attack.mitre.org/software/S1042) is a proprietary browser credential harvesting tool that was used by UNC3890 during the [C0010](https://attack.mitre.org/campaigns/C0010) campaign. The first known [SUGARDUMP](https://attack.mitre.org/software/S1042) version was used since at least early 2021, a second SMTP C2 version was used from late 2021-early 2022, and a third HTTP C2 variant was used since at least April 2022.(Citation: Mandiant UNC3890 Aug 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1042](https://attack.mitre.org/software/S1042)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
