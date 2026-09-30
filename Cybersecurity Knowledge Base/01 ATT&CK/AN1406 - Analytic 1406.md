---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1406"
source_url: "https://attack.mitre.org/detectionstrategies/DET0509#AN1406"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1406: Analytic 1406

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1406  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

Detects use of session cookies or authentication tokens from unusual user agents or locations. Identifies token reuse without reauthentication or attempts to bypass MFA using previously stolen cookies.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1406](https://attack.mitre.org/detectionstrategies/DET0509#AN1406)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
