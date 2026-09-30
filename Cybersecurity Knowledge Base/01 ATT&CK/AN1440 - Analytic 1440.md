---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1440"
source_url: "https://attack.mitre.org/detectionstrategies/DET0521#AN1440"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1440: Analytic 1440

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1440  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects suspicious use of PowerShell, .NET, or script interpreters to spawn processes that mimic UAC prompts, often with credential capture dialogue boxes invoked from non-standard parent processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1440](https://attack.mitre.org/detectionstrategies/DET0521#AN1440)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
