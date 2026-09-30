---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0492"
source_url: "https://attack.mitre.org/detectionstrategies/DET0173#AN0492"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0492: Analytic 0492

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0492  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Automated or scripted HTTP/TLS flooding from one VM or cloud instance against another service, exploiting compute-based billing or exhaustion of service infrastructure.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0492](https://attack.mitre.org/detectionstrategies/DET0173#AN0492)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
