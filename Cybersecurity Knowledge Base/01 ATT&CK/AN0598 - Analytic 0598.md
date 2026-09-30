---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0598"
source_url: "https://attack.mitre.org/detectionstrategies/DET0213#AN0598"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0598: Analytic 0598

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0598  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Processes on macOS initiate external connections that consistently transmit data in fixed sizes using LaunchAgents or unexpected users.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0598](https://attack.mitre.org/detectionstrategies/DET0213#AN0598)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
