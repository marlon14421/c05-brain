---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1112"
source_url: "https://attack.mitre.org/detectionstrategies/DET0396#AN1112"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1112: Analytic 1112

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1112  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects suspicious access to macOS Keychain files and APIs. Observes processes invoking the 'security' utility or accessing Keychain databases directly, correlates these with abnormal parent process lineage or unexpected user context. Monitors attempts to dump, unlock, or read credential storage beyond normal application workflows.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1112](https://attack.mitre.org/detectionstrategies/DET0396#AN1112)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
