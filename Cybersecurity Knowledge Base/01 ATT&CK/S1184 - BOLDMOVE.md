---
type: "Malware"
source: MITRE ATT&CK
id: "S1184"
source_url: "https://attack.mitre.org/software/S1184"
created: "2024-12-31"
modified: "2025-04-15"
---
# S1184: BOLDMOVE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1184  
**Platforms:** Linux, Network Devices  
**Tactics:** Not specified

## Source description

[BOLDMOVE](https://attack.mitre.org/software/S1184) is a type of backdoor malware written in C linked to People’s Republic of China operations from 2022 through 2023. [BOLDMOVE](https://attack.mitre.org/software/S1184) includes both Windows and Linux variants, with some Linux variants specifically designed for FortiGate Firewall devices. [BOLDMOVE](https://attack.mitre.org/software/S1184) is linked to zero-day exploitation of CVE-2022-42475 in FortiOSS SSL-VPNs.(Citation: Google Cloud BOLDMOVE 2023) The record for [BOLDMOVE](https://attack.mitre.org/software/S1184) only covers known Linux variants.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1184](https://attack.mitre.org/software/S1184)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
