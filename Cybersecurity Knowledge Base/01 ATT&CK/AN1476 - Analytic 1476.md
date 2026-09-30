---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1476"
source_url: "https://attack.mitre.org/detectionstrategies/DET0536#AN1476"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1476: Analytic 1476

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1476  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects anomalous wireless connections such as unexpected SSID associations, failed or repeated authentication attempts, and connections outside of known geofenced networks. Defenders should monitor wireless connection logs and event codes for network discovery, authentication, and association events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1476](https://attack.mitre.org/detectionstrategies/DET0536#AN1476)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
