---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1131"
source_url: "https://attack.mitre.org/detectionstrategies/DET0403#AN1131"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1131: Analytic 1131

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1131  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Configuration changes to virtual TAP/mirror policies that forward traffic to unapproved destinations. Detection correlates management plane API calls with mirrored traffic observation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1131](https://attack.mitre.org/detectionstrategies/DET0403#AN1131)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
