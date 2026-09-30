---
type: "Malware"
source: MITRE ATT&CK
id: "S1120"
source_url: "https://attack.mitre.org/software/S1120"
created: "2024-03-08"
modified: "2025-04-15"
---
# S1120: FRAMESTING

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1120  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[FRAMESTING](https://attack.mitre.org/software/S1120) is a Python web shell that was used during [Cutting Edge](https://attack.mitre.org/campaigns/C0029) to embed into an Ivanti Connect Secure Python package for command execution.(Citation: Mandiant Cutting Edge Part 2 January 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1120](https://attack.mitre.org/software/S1120)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
