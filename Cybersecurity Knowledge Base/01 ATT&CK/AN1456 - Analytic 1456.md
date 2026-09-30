---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1456"
source_url: "https://attack.mitre.org/detectionstrategies/DET0525#AN1456"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1456: Analytic 1456

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1456  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Use of cloud API calls (e.g., AWS EC2 DescribeInstances, Azure VM Inventory) to enumerate system configurations across assets.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1456](https://attack.mitre.org/detectionstrategies/DET0525#AN1456)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
