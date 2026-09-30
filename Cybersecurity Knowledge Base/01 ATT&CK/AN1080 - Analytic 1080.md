---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1080"
source_url: "https://attack.mitre.org/detectionstrategies/DET0383#AN1080"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1080: Analytic 1080

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1080  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Monitors for the creation of accounts inside containers using names that resemble legitimate orchestrator or backup identities to mask adversary persistence.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1080](https://attack.mitre.org/detectionstrategies/DET0383#AN1080)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
