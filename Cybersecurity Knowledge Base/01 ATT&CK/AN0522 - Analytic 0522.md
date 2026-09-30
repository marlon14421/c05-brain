---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0522"
source_url: "https://attack.mitre.org/detectionstrategies/DET0184#AN0522"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0522: Analytic 0522

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0522  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects clearing of unified logs, deletion of plist files tied to persistence, and manipulation of Terminal history after initial execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0522](https://attack.mitre.org/detectionstrategies/DET0184#AN0522)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
