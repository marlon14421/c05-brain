---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1161"
source_url: "https://attack.mitre.org/detectionstrategies/DET0413#AN1161"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1161: Analytic 1161

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1161  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Command-line tools (e.g., curl, rsync, wget, or custom Python scripts) used to scrape documentation systems or internal REST APIs. Unusual access patterns to knowledge base folders or shared team drives.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1161](https://attack.mitre.org/detectionstrategies/DET0413#AN1161)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
