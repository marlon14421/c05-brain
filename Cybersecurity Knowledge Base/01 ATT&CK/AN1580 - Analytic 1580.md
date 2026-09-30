---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1580"
source_url: "https://attack.mitre.org/detectionstrategies/DET0573#AN1580"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1580: Analytic 1580

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1580  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects snapshot sharing, backup exports, or data object transfers from victim-owned cloud accounts to other cloud identities within the same provider (e.g., AWS, Azure) using snapshot sharing, S3 bucket policy updates, or SAS URI generation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1580](https://attack.mitre.org/detectionstrategies/DET0573#AN1580)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
