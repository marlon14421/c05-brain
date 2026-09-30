---
type: "Malware"
source: MITRE ATT&CK
id: "S0226"
source_url: "https://attack.mitre.org/software/S0226"
created: "2018-04-18"
modified: "2024-04-11"
---
# S0226: Smoke Loader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0226  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Smoke Loader](https://attack.mitre.org/software/S0226) is a malicious bot application that can be used to load other malware. [Smoke Loader](https://attack.mitre.org/software/S0226) has been seen in the wild since at least 2011 and has included a number of different payloads. It is notorious for its use of deception and self-protection. It also comes with several plug-ins. (Citation: Malwarebytes SmokeLoader 2016) (Citation: Microsoft Dofoil 2018)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0226](https://attack.mitre.org/software/S0226)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
