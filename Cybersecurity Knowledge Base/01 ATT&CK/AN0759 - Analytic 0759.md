---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0759"
source_url: "https://attack.mitre.org/detectionstrategies/DET0273#AN0759"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0759: Analytic 0759

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0759  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes that normally do not initiate network connections establishing outbound encrypted TLS/SSL sessions, especially with asymmetric traffic volumes (client sending more than receiving) or non-standard certificate chains. Defender observations correlate process creation with unexpected network encryption libraries being loaded.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0759](https://attack.mitre.org/detectionstrategies/DET0273#AN0759)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
