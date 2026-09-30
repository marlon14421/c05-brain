---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0489"
source_url: "https://attack.mitre.org/detectionstrategies/DET0173#AN0489"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0489: Analytic 0489

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0489  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

High-frequency, repetitive service requests (e.g., HTTP, TLS renegotiation) originating from a single or small set of source IPs targeting endpoint web services or application ports, leading to exhaustion of CPU or memory on targeted Windows services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0489](https://attack.mitre.org/detectionstrategies/DET0173#AN0489)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
