---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0827"
source_url: "https://attack.mitre.org/detectionstrategies/DET0297#AN0827"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0827: Analytic 0827

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0827  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes attempting raw disk access to overwrite sensitive structures such as the MBR or partition table using \\.\PhysicalDrive notation. Detection relies on correlating process creation, privilege escalation, and raw sector writes in Sysmon and Security logs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0827](https://attack.mitre.org/detectionstrategies/DET0297#AN0827)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
