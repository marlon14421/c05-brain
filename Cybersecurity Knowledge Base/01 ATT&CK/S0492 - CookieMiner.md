---
type: "Malware"
source: MITRE ATT&CK
id: "S0492"
source_url: "https://attack.mitre.org/software/S0492"
created: "2020-07-22"
modified: "2025-04-16"
---
# S0492: CookieMiner

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0492  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

[CookieMiner](https://attack.mitre.org/software/S0492) is mac-based malware that targets information associated with cryptocurrency exchanges as well as enabling cryptocurrency mining on the victim system itself. It was first discovered in the wild in 2019.(Citation: Unit42 CookieMiner Jan 2019)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0492](https://attack.mitre.org/software/S0492)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
