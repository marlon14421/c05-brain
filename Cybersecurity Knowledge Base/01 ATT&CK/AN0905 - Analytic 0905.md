---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0905"
source_url: "https://attack.mitre.org/detectionstrategies/DET0320#AN0905"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0905: Analytic 0905

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0905  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects shell-based enumeration of active connections using `netstat`, `lsof -i`, or AppleScript-based system discovery.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0905](https://attack.mitre.org/detectionstrategies/DET0320#AN0905)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
