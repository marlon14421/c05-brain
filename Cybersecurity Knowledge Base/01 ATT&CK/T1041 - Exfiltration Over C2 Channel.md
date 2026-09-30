---
type: "Technique"
source: MITRE ATT&CK
id: "T1041"
source_url: "https://attack.mitre.org/techniques/T1041"
created: "2017-05-31"
modified: "2026-05-12"
---
# T1041: Exfiltration Over C2 Channel

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1041  
**Platforms:** ESXi, Linux, macOS, Windows  
**Tactics:** exfiltration

## Source description

Adversaries may steal data by exfiltrating it over an existing command and control channel. Stolen data is encoded into the normal communications channel using the same protocol as command and control communications.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1041](https://attack.mitre.org/techniques/T1041)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
