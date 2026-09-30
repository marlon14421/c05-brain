---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1099"
source_url: "https://attack.mitre.org/detectionstrategies/DET0391#AN1099"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1099: Analytic 1099

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1099  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Monitor for runtime manipulation by observing changes in application bundles, unexpected signing modifications, and runtime API calls that inject or alter how data is displayed. Detect alterations in CFNetwork or CoreFoundation frameworks responsible for rendering data.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1099](https://attack.mitre.org/detectionstrategies/DET0391#AN1099)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
