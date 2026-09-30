---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0326"
source_url: "https://attack.mitre.org/detectionstrategies/DET0117#AN0326"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0326: Analytic 0326

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0326  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Creation of LaunchAgents or LaunchDaemons with names resembling known system services but executing non-Apple signed code or scripts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0326](https://attack.mitre.org/detectionstrategies/DET0117#AN0326)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
