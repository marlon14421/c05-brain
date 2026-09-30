---
type: "Malware"
source: MITRE ATT&CK
id: "S1115"
source_url: "https://attack.mitre.org/software/S1115"
created: "2024-03-04"
modified: "2025-04-15"
---
# S1115: WIREFIRE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1115  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[WIREFIRE](https://attack.mitre.org/software/S1115) is a web shell written in Python that exists as trojanized logic to the visits.py component of Ivanti Connect Secure VPN appliances. [WIREFIRE](https://attack.mitre.org/software/S1115) was used during [Cutting Edge](https://attack.mitre.org/campaigns/C0029) for downloading files and command execution.(Citation: Mandiant Cutting Edge January 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1115](https://attack.mitre.org/software/S1115)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
