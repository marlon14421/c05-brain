---
type: "Malware"
source: MITRE ATT&CK
id: "S1110"
source_url: "https://attack.mitre.org/software/S1110"
created: "2024-02-09"
modified: "2025-04-15"
---
# S1110: SLIGHTPULSE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1110  
**Platforms:** Network Devices, Linux  
**Tactics:** Not specified

## Source description

[SLIGHTPULSE](https://attack.mitre.org/software/S1110) is a web shell that was used by [APT5](https://attack.mitre.org/groups/G1023) as early as 2020 including against Pulse Secure VPNs at US Defense Industrial Base (DIB) entities.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1110](https://attack.mitre.org/software/S1110)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
