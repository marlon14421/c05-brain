---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0566"
source_url: "https://attack.mitre.org/detectionstrategies/DET0196#AN0566"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0566: Analytic 0566

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0566  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Unsigned or user-space apps initiate TLS connections with one hostname and HTTP headers requesting a different domain, commonly abused in CDN-resident domain fronting techniques.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0566](https://attack.mitre.org/detectionstrategies/DET0196#AN0566)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
