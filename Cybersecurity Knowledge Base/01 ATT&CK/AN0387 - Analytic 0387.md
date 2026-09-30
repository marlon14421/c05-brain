---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0387"
source_url: "https://attack.mitre.org/detectionstrategies/DET0137#AN0387"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0387: Analytic 0387

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0387  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Execution of destructive CLI commands such as 'erase startup-config', 'erase flash:' or 'format disk' on routers/switches. Detect privilege level escalation preceding destructive commands.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0387](https://attack.mitre.org/detectionstrategies/DET0137#AN0387)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
