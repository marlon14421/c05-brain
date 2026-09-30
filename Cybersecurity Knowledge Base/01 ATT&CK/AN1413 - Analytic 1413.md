---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1413"
source_url: "https://attack.mitre.org/detectionstrategies/DET0512#AN1413"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1413: Analytic 1413

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1413  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects non-browser processes that establish encrypted outbound connections (e.g., TLS/SSL) to unfamiliar or atypical destinations for the host/user, following a data staging or compression event.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1413](https://attack.mitre.org/detectionstrategies/DET0512#AN1413)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
