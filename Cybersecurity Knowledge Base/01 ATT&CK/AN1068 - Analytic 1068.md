---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1068"
source_url: "https://attack.mitre.org/detectionstrategies/DET0378#AN1068"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1068: Analytic 1068

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1068  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects encoded PowerCLI or Base64-encoded payloads staged via datastore uploads or shell access (e.g., ESXi Shell or backdoored VIBs).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1068](https://attack.mitre.org/detectionstrategies/DET0378#AN1068)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
