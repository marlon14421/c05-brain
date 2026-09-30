---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0136"
source_url: "https://attack.mitre.org/detectionstrategies/DET0049#AN0136"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0136: Analytic 0136

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0136  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects firewall rule modifications or reset of logs/connection tables (e.g., `clear logging`, `erase startup-config`, `write erase`) following remote access activity on routers, switches, or VPN appliances.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0136](https://attack.mitre.org/detectionstrategies/DET0049#AN0136)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
