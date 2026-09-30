---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1405"
source_url: "https://attack.mitre.org/detectionstrategies/DET0509#AN1405"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1405: Analytic 1405

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1405  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Detects automation macros or VBA scripts in documents that access browser file paths, read cookie data, or attempt to exfiltrate browser session tokens over HTTP.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1405](https://attack.mitre.org/detectionstrategies/DET0509#AN1405)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
