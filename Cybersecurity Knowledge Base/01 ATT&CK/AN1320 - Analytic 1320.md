---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1320"
source_url: "https://attack.mitre.org/detectionstrategies/DET0480#AN1320"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1320: Analytic 1320

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1320  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects unauthorized modifications to login-facing web server files (e.g., index.php, login.js) typically tied to VPN, SSO, or intranet portals. Correlates suspicious file changes with remote access artifacts or web shell behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1320](https://attack.mitre.org/detectionstrategies/DET0480#AN1320)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
