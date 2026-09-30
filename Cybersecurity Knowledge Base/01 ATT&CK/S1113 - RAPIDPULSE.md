---
type: "Malware"
source: MITRE ATT&CK
id: "S1113"
source_url: "https://attack.mitre.org/software/S1113"
created: "2024-02-13"
modified: "2025-04-15"
---
# S1113: RAPIDPULSE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1113  
**Platforms:** Network Devices, Linux  
**Tactics:** Not specified

## Source description

[RAPIDPULSE](https://attack.mitre.org/software/S1113) is a web shell that exists as a modification to a legitimate Pulse Secure file that has been used by [APT5](https://attack.mitre.org/groups/G1023) since at least 2021.(Citation: Mandiant Pulse Secure Update May 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1113](https://attack.mitre.org/software/S1113)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
