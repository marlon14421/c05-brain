---
type: "Malware"
source: MITRE ATT&CK
id: "S0624"
source_url: "https://attack.mitre.org/software/S0624"
created: "2021-06-18"
modified: "2025-04-25"
---
# S0624: Ecipekac

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0624  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Ecipekac](https://attack.mitre.org/software/S0624) is a multi-layer loader that has been used by [menuPass](https://attack.mitre.org/groups/G0045) since at least 2019 including use as a loader for [P8RAT](https://attack.mitre.org/software/S0626), [SodaMaster](https://attack.mitre.org/software/S0627), and [FYAnti](https://attack.mitre.org/software/S0628).(Citation: Securelist APT10 March 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0624](https://attack.mitre.org/software/S0624)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
