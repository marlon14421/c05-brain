---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1512"
source_url: "https://attack.mitre.org/detectionstrategies/DET0548#AN1512"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1512: Analytic 1512

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1512  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Processes (tar, curl, python scripts) accessing large file sets and initiating outbound HTTPS POST requests with payload sizes inconsistent with baseline activity. Defender perspective: detect abnormal sequence of file archival followed by encrypted uploads to external web services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1512](https://attack.mitre.org/detectionstrategies/DET0548#AN1512)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
