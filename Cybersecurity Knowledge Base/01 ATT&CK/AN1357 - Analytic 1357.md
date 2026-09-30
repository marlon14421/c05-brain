---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1357"
source_url: "https://attack.mitre.org/detectionstrategies/DET0493#AN1357"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1357: Analytic 1357

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1357  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects anomalous use of COM, DDE, or named pipes for execution. Correlates creation or access of IPC mechanisms (e.g., named pipes, COM objects) with unusual parent-child process relationships or code injection patterns (e.g., Office spawning cmd.exe via DDE).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1357](https://attack.mitre.org/detectionstrategies/DET0493#AN1357)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
