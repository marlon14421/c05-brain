---
type: "Malware"
source: MITRE ATT&CK
id: "S0603"
source_url: "https://attack.mitre.org/software/S0603"
created: "2020-12-14"
modified: "2026-04-24"
---
# S0603: Stuxnet

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0603  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Stuxnet](https://attack.mitre.org/software/S0603) was the first publicly reported malware to specifically target industrial control systems devices. [Stuxnet](https://attack.mitre.org/software/S0603) is a large and complex malware that utilized multiple behaviors, including numerous zero-day vulnerabilities, a sophisticated Windows rootkit, and network infection routines.(Citation: Nicolas Falliere, Liam O Murchu, Eric Chien February 2011)(Citation: CISA ICS Advisory ICSA-10-272-01)(Citation: ESET Stuxnet Under the Microscope)(Citation: Langer Stuxnet) [Stuxnet](https://attack.mitre.org/software/S0603) was discovered in 2010, with some components being used as early as November 2008.(Citation: Nicolas Falliere, Liam O Murchu, Eric Chien February 2011)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0603](https://attack.mitre.org/software/S0603)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
