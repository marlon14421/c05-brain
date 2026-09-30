---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0281"
source_url: "https://attack.mitre.org/detectionstrategies/DET0101#AN0281"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0281: Analytic 0281

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0281  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects embedded Lua interpreter execution or script injection on devices supporting Lua scripting (e.g., routers, firewalls), often seen in modified firmware or abused APIs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0281](https://attack.mitre.org/detectionstrategies/DET0101#AN0281)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
