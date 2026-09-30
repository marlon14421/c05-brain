---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0975"
source_url: "https://attack.mitre.org/detectionstrategies/DET0345#AN0975"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0975: Analytic 0975

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0975  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlate registry modifications (e.g., UAC bypass registry keys), unusual parent-child process relationships (e.g., control.exe spawning cmd.exe), and unsigned elevated process executions with non-standard tokens or elevation flags.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0975](https://attack.mitre.org/detectionstrategies/DET0345#AN0975)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
