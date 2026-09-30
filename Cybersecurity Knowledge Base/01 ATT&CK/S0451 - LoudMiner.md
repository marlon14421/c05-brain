---
type: "Malware"
source: MITRE ATT&CK
id: "S0451"
source_url: "https://attack.mitre.org/software/S0451"
created: "2020-05-18"
modified: "2024-04-11"
---
# S0451: LoudMiner

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0451  
**Platforms:** macOS, Windows  
**Tactics:** Not specified

## Source description

[LoudMiner](https://attack.mitre.org/software/S0451) is a cryptocurrency miner which uses virtualization software to siphon system resources. The miner has been bundled with pirated copies of Virtual Studio Technology (VST) for Windows and macOS.(Citation: ESET LoudMiner June 2019)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0451](https://attack.mitre.org/software/S0451)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
