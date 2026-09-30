---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1468"
source_url: "https://attack.mitre.org/detectionstrategies/DET0530#AN1468"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1468: Analytic 1468

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1468  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

An SMB-based remote file share access followed by lateral movement actions such as remote service creation, task scheduling, or suspicious process execution on the target host using ADMIN$ or C$ shares.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1468](https://attack.mitre.org/detectionstrategies/DET0530#AN1468)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
