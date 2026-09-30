---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1624"
source_url: "https://attack.mitre.org/detectionstrategies/DET0590#AN1624"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1624: Analytic 1624

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1624  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Adversary modifies web-facing content on macOS via web development environments like MAMP or misconfigured Apache instances, typically with access to the hosting user account or via persistence tools.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1624](https://attack.mitre.org/detectionstrategies/DET0590#AN1624)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
