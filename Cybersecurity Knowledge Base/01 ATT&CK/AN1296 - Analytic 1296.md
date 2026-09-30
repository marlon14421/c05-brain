---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1296"
source_url: "https://attack.mitre.org/detectionstrategies/DET0470#AN1296"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1296: Analytic 1296

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1296  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Unsigned or suspicious applications initiating network traffic claiming to be browser, mail, or cloud clients. Detects impersonation via TLS fingerprint and User-Agent string deviation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1296](https://attack.mitre.org/detectionstrategies/DET0470#AN1296)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
