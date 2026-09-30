---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1542"
source_url: "https://attack.mitre.org/detectionstrategies/DET0559#AN1542"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1542: Analytic 1542

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1542  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Monitor CLI 'reload' commands issued without scheduled maintenance, and correlate to TACACS+/AAA logs for privilege validation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1542](https://attack.mitre.org/detectionstrategies/DET0559#AN1542)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
