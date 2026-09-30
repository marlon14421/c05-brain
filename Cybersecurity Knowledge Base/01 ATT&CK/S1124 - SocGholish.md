---
type: "Malware"
source: MITRE ATT&CK
id: "S1124"
source_url: "https://attack.mitre.org/software/S1124"
created: "2024-03-22"
modified: "2024-04-06"
---
# S1124: SocGholish

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1124  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SocGholish](https://attack.mitre.org/software/S1124) is a JavaScript-based loader malware that has been used since at least 2017. It has been observed in use against multiple sectors globally for initial access, primarily through drive-by-downloads masquerading as software updates. SocGholish is operated by [Mustard Tempest](https://attack.mitre.org/groups/G1020) and its access has been sold to groups including [Indrik Spider](https://attack.mitre.org/groups/G0119) for downloading secondary RAT and ransomware payloads.(Citation: SentinelOne SocGholish Infrastructure November 2022)(Citation: SocGholish-update)(Citation: Red Canary SocGholish March 2024)(Citation: Secureworks Gold Prelude Profile)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1124](https://attack.mitre.org/software/S1124)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
