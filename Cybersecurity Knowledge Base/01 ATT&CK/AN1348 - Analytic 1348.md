---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1348"
source_url: "https://attack.mitre.org/detectionstrategies/DET0488#AN1348"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1348: Analytic 1348

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1348  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Behavioral chain: (1) cross-account or third-party principal assumes a role into the tenant/subscription/project; (2) privileged API calls are made in short succession; (3) access originates from unfamiliar networks or geos. Correlate assume-role/federation events with sensitive API usage.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1348](https://attack.mitre.org/detectionstrategies/DET0488#AN1348)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
