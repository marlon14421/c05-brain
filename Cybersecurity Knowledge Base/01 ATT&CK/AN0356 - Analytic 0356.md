---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0356"
source_url: "https://attack.mitre.org/detectionstrategies/DET0127#AN0356"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0356: Analytic 0356

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0356  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Adversary drops renamed binaries in uncommon directories (e.g., /tmp, /dev/shm) or uses special characters in names (e.g., trailing space, Unicode RLO). Execution or cronjob registration follows shortly after file drop.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0356](https://attack.mitre.org/detectionstrategies/DET0127#AN0356)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
