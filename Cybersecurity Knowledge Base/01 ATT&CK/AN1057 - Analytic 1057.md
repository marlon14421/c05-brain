---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1057"
source_url: "https://attack.mitre.org/detectionstrategies/DET0376#AN1057"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1057: Analytic 1057

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1057  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects processes performing network enumeration (e.g., port scans, service probing) by correlating process creation, socket connections, and sequential destination IP probing within a time window.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1057](https://attack.mitre.org/detectionstrategies/DET0376#AN1057)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
