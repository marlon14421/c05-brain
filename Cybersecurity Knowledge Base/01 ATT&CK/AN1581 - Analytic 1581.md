---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1581"
source_url: "https://attack.mitre.org/detectionstrategies/DET0573#AN1581"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1581: Analytic 1581

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1581  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Detects user activity that shares or syncs files with external domains via link generation, OneDrive external sharing, or file transfer actions involving non-whitelisted partner tenants.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1581](https://attack.mitre.org/detectionstrategies/DET0573#AN1581)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
