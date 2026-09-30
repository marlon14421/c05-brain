---
type: "Malware"
source: MITRE ATT&CK
id: "S1119"
source_url: "https://attack.mitre.org/software/S1119"
created: "2024-03-07"
modified: "2025-04-15"
---
# S1119: LIGHTWIRE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1119  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[LIGHTWIRE](https://attack.mitre.org/software/S1119) is a web shell written in Perl that was used during [Cutting Edge](https://attack.mitre.org/campaigns/C0029) to maintain access and enable command execution by imbedding into the legitimate compcheckresult.cgi component of Ivanti Secure Connect VPNs.(Citation: Mandiant Cutting Edge Part 2 January 2024)(Citation: Mandiant Cutting Edge January 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1119](https://attack.mitre.org/software/S1119)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
