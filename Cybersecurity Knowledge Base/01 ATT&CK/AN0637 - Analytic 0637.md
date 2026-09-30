---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0637"
source_url: "https://attack.mitre.org/detectionstrategies/DET0228#AN0637"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0637: Analytic 0637

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0637  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Initial process initiates outbound connection to first-stage C2, receives payloads or commands, then spawns or injects into a second process that establishes a new outbound connection to an unrelated destination (second-stage C2).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0637](https://attack.mitre.org/detectionstrategies/DET0228#AN0637)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
