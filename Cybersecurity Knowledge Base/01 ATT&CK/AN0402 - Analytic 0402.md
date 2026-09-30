---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0402"
source_url: "https://attack.mitre.org/detectionstrategies/DET0143#AN0402"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0402: Analytic 0402

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0402  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Launchd jobs or user processes invoking symmetric crypto APIs from the Security framework and generating outbound connections carrying randomized payloads inconsistent with normal TLS patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0402](https://attack.mitre.org/detectionstrategies/DET0143#AN0402)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
