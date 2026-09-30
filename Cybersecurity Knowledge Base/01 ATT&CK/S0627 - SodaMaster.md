---
type: "Malware"
source: MITRE ATT&CK
id: "S0627"
source_url: "https://attack.mitre.org/software/S0627"
created: "2021-06-21"
modified: "2025-04-25"
---
# S0627: SodaMaster

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0627  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SodaMaster](https://attack.mitre.org/software/S0627) is a fileless malware used by [menuPass](https://attack.mitre.org/groups/G0045) to download and execute payloads since at least 2020.(Citation: Securelist APT10 March 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0627](https://attack.mitre.org/software/S0627)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
