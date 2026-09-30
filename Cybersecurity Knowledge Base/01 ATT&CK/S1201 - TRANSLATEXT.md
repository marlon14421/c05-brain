---
type: "Malware"
source: MITRE ATT&CK
id: "S1201"
source_url: "https://attack.mitre.org/software/S1201"
created: "2025-01-29"
modified: "2025-02-05"
---
# S1201: TRANSLATEXT

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1201  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[TRANSLATEXT](https://attack.mitre.org/software/S1201) is malware that is believed to be used by [Kimsuky](https://attack.mitre.org/groups/G0094).(Citation: Zscaler Kimsuky TRANSLATEXT) [TRANSLATEXT](https://attack.mitre.org/software/S1201) masqueraded as a Google Translate extension for Google Chrome, but is actually a collection of four malicious Javascript files that perform defense evasion, information collection and exfiltration.(Citation: Zscaler Kimsuky TRANSLATEXT)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1201](https://attack.mitre.org/software/S1201)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
