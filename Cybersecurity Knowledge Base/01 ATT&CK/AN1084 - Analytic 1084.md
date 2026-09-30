---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1084"
source_url: "https://attack.mitre.org/detectionstrategies/DET0384#AN1084"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1084: Analytic 1084

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1084  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects Unix shell usage on network appliances (e.g., routers, firewalls, embedded Linux) through rare console commands, CLI interfaces, or script injection via exposed APIs or SSH.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1084](https://attack.mitre.org/detectionstrategies/DET0384#AN1084)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
