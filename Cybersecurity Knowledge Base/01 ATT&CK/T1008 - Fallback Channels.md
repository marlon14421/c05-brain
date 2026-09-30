---
type: "Technique"
source: MITRE ATT&CK
id: "T1008"
source_url: "https://attack.mitre.org/techniques/T1008"
created: "2017-05-31"
modified: "2026-05-12"
---
# T1008: Fallback Channels

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1008  
**Platforms:** ESXi, Linux, macOS, Windows  
**Tactics:** command-and-control

## Source description

Adversaries may use fallback or alternate communication channels if the primary channel is compromised or inaccessible in order to maintain reliable command and control and to avoid data transfer thresholds.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1008](https://attack.mitre.org/techniques/T1008)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
