---
type: "Malware"
source: MITRE ATT&CK
id: "S0687"
source_url: "https://attack.mitre.org/software/S0687"
created: "2022-03-03"
modified: "2026-05-12"
---
# S0687: Cyclops Blink

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0687  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[Cyclops Blink](https://attack.mitre.org/software/S0687) is a modular malware that has been used in widespread campaigns by [Sandworm Team](https://attack.mitre.org/groups/G0034) since at least 2019 to target Small/Home Office (SOHO) network devices, including WatchGuard and Asus. [Cyclops Blink](https://attack.mitre.org/software/S0687) is assessed to be a replacement for [VPNFilter](https://attack.mitre.org/software/S1010), a similar platform targeting network devices.(Citation: NCSC Cyclops Blink February 2022)(Citation: NCSC CISA Cyclops Blink Advisory February 2022)(Citation: Trend Micro Cyclops Blink March 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0687](https://attack.mitre.org/software/S0687)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
