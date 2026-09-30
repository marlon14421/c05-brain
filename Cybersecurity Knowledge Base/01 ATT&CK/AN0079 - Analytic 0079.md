---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0079"
source_url: "https://attack.mitre.org/detectionstrategies/DET0027#AN0079"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0079: Analytic 0079

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0079  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects Web protocol misuse such as encoded HTTP headers, WebSocket upgrade requests with abnormal payloads, or TLS handshake anomalies suggesting embedded C2 channels.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0079](https://attack.mitre.org/detectionstrategies/DET0027#AN0079)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
