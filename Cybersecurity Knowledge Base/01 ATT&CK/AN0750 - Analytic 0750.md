---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0750"
source_url: "https://attack.mitre.org/detectionstrategies/DET0269#AN0750"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0750: Analytic 0750

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0750  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Logon via RDP or WMI by a user account followed by uncommon command execution, file manipulation, or lateral network connections.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0750](https://attack.mitre.org/detectionstrategies/DET0269#AN0750)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
