---
type: "Malware"
source: MITRE ATT&CK
id: "S0086"
source_url: "https://attack.mitre.org/software/S0086"
created: "2017-05-31"
modified: "2025-04-16"
---
# S0086: ZLib

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0086  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[ZLib](https://attack.mitre.org/software/S0086) is a full-featured backdoor that was used as a second-stage implant during [Operation Dust Storm](https://attack.mitre.org/campaigns/C0016) since at least 2014. [ZLib](https://attack.mitre.org/software/S0086) is malware and should not be confused with the legitimate compression library from which its name is derived.(Citation: Cylance Dust Storm)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0086](https://attack.mitre.org/software/S0086)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
