---
type: "Malware"
source: MITRE ATT&CK
id: "S1117"
source_url: "https://attack.mitre.org/software/S1117"
created: "2024-03-06"
modified: "2025-04-15"
---
# S1117: GLASSTOKEN

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1117  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[GLASSTOKEN](https://attack.mitre.org/software/S1117) is a custom web shell used by threat actors during [Cutting Edge](https://attack.mitre.org/campaigns/C0029) to execute commands on compromised Ivanti Secure Connect VPNs.(Citation: Volexity Ivanti Zero-Day Exploitation January 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1117](https://attack.mitre.org/software/S1117)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
