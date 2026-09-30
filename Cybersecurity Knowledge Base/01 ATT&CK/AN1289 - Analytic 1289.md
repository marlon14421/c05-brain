---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1289"
source_url: "https://attack.mitre.org/detectionstrategies/DET0467#AN1289"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1289: Analytic 1289

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1289  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects thread local storage (TLS) callback injection by monitoring memory modifications to PE headers and TLS directory structures during or after process hollowing events, followed by anomalous thread behavior prior to main entry point execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1289](https://attack.mitre.org/detectionstrategies/DET0467#AN1289)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
