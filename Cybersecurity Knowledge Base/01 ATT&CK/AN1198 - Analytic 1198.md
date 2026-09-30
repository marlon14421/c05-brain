---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1198"
source_url: "https://attack.mitre.org/detectionstrategies/DET0430#AN1198"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1198: Analytic 1198

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1198  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitors suspicious access to password stores such as LSASS, DPAPI, Windows Credential Manager, or browser credential databases. Detects anomalous process-to-process access (e.g., Mimikatz accessing LSASS) and correlation of credential store file reads with execution of non-standard processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1198](https://attack.mitre.org/detectionstrategies/DET0430#AN1198)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
