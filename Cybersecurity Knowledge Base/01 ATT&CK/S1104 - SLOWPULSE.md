---
type: "Malware"
source: MITRE ATT&CK
id: "S1104"
source_url: "https://attack.mitre.org/software/S1104"
created: "2024-02-06"
modified: "2025-04-15"
---
# S1104: SLOWPULSE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1104  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[SLOWPULSE](https://attack.mitre.org/software/S1104) is a malware that was used by [APT5](https://attack.mitre.org/groups/G1023) as early as 2020 including against U.S. Defense Industrial Base (DIB) companies. [SLOWPULSE](https://attack.mitre.org/software/S1104) has several variants and can modify legitimate Pulse Secure VPN files in order to log credentials and bypass single and two-factor authentication flows.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1104](https://attack.mitre.org/software/S1104)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
