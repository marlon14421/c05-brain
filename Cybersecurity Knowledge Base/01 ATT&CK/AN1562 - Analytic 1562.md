---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1562"
source_url: "https://attack.mitre.org/detectionstrategies/DET0565#AN1562"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1562: Analytic 1562

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1562  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Processes executing commands to query system locale and language settings, such as 'locale', 'echo $LANG', or parsing environment variables. Suspicious activity is indicated by these commands being run by unusual users, automation scripts, or non-administrative processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1562](https://attack.mitre.org/detectionstrategies/DET0565#AN1562)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
