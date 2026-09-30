---
type: "Malware"
source: MITRE ATT&CK
id: "S0599"
source_url: "https://attack.mitre.org/software/S0599"
created: "2021-04-06"
modified: "2025-04-25"
---
# S0599: Kinsing

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0599  
**Platforms:** Containers, Linux  
**Tactics:** Not specified

## Source description

[Kinsing](https://attack.mitre.org/software/S0599) is Golang-based malware that runs a cryptocurrency miner and attempts to spread itself to other hosts in the victim environment. (Citation: Aqua Kinsing April 2020)(Citation: Sysdig Kinsing November 2020)(Citation: Aqua Security Cloud Native Threat Report June 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0599](https://attack.mitre.org/software/S0599)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
