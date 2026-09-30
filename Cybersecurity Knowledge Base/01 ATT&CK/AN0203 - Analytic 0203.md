---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0203"
source_url: "https://attack.mitre.org/detectionstrategies/DET0074#AN0203"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0203: Analytic 0203

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0203  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Web session tokens reused in native Office apps (e.g., Outlook, Teams) without associated token refresh or login behavior on the endpoint.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0203](https://attack.mitre.org/detectionstrategies/DET0074#AN0203)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
