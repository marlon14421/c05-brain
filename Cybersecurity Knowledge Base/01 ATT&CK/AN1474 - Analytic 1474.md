---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1474"
source_url: "https://attack.mitre.org/detectionstrategies/DET0534#AN1474"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1474: Analytic 1474

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1474  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Unauthorized modification of TCC.db followed by elevated process execution under a trusted parent (e.g., Finder, SystemUIServer) or via launchctl environment override. Also includes identification of SIP being disabled, which is highly uncommon and a prerequisite for this abuse path.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1474](https://attack.mitre.org/detectionstrategies/DET0534#AN1474)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
