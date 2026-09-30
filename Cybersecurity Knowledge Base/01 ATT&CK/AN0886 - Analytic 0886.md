---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0886"
source_url: "https://attack.mitre.org/detectionstrategies/DET0317#AN0886"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0886: Analytic 0886

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0886  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unusual service stop events, termination of AV/EDR processes, registry modifications disabling security tools, and firewall/defender configuration changes. Correlate process creation with service stop requests and registry edits.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0886](https://attack.mitre.org/detectionstrategies/DET0317#AN0886)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
