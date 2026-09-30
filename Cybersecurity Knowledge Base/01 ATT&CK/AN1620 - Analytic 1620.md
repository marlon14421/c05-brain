---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1620"
source_url: "https://attack.mitre.org/detectionstrategies/DET0588#AN1620"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1620: Analytic 1620

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1620  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of suspicious use of `tscon.exe` or equivalent methods to hijack legitimate RDP sessions. Defenders can observe anomalies such as session reassignments without corresponding authentication, processes spawned in the context of hijacked sessions, or unusual RDP network traffic flows that deviate from expected baselines.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1620](https://attack.mitre.org/detectionstrategies/DET0588#AN1620)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
