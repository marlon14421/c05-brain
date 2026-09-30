---
type: "Malware"
source: MITRE ATT&CK
id: "S1121"
source_url: "https://attack.mitre.org/software/S1121"
created: "2024-03-13"
modified: "2025-04-15"
---
# S1121: LITTLELAMB.WOOLTEA

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1121  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[LITTLELAMB.WOOLTEA](https://attack.mitre.org/software/S1121) is a backdoor that was used by UNC5325 during [Cutting Edge](https://attack.mitre.org/campaigns/C0029) to deploy malware on targeted Ivanti Connect Secure VPNs and to establish persistence across system upgrades and patches.(Citation: Mandiant Cutting Edge Part 3 February 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1121](https://attack.mitre.org/software/S1121)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
