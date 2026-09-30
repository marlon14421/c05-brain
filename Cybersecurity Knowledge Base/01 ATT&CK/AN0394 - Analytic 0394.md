---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0394"
source_url: "https://attack.mitre.org/detectionstrategies/DET0140#AN0394"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0394: Analytic 0394

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0394  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects removal of adversary artifacts via `rm`, `unlink`, or secure tools, with focus on shell sessions, temp files, and modified LaunchAgents or system directories.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0394](https://attack.mitre.org/detectionstrategies/DET0140#AN0394)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
