---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1333"
source_url: "https://attack.mitre.org/detectionstrategies/DET0485#AN1333"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1333: Analytic 1333

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1333  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Use unified logs to identify processes issuing repeated DNS queries where the resolved IP addresses change frequently within very short TTL values. Correlate with outbound network traffic to validate C2-like patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1333](https://attack.mitre.org/detectionstrategies/DET0485#AN1333)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
