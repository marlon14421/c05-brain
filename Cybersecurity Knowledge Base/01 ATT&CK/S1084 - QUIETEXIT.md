---
type: "Malware"
source: MITRE ATT&CK
id: "S1084"
source_url: "https://attack.mitre.org/software/S1084"
created: "2023-08-17"
modified: "2025-04-15"
---
# S1084: QUIETEXIT

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1084  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[QUIETEXIT](https://attack.mitre.org/software/S1084) is a novel backdoor, based on the open-source Dropbear SSH client-server software, that has been used by [APT29](https://attack.mitre.org/groups/G0016) since at least 2021. [APT29](https://attack.mitre.org/groups/G0016) has deployed [QUIETEXIT](https://attack.mitre.org/software/S1084) on opaque network appliances that typically don't support antivirus or endpoint detection and response tools within a victim environment.(Citation: Mandiant APT29 Eye Spy Email Nov 22)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1084](https://attack.mitre.org/software/S1084)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
