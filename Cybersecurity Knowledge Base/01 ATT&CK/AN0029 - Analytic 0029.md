---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0029"
source_url: "https://attack.mitre.org/detectionstrategies/DET0010#AN0029"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0029: Analytic 0029

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0029  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Detects macros or VBA triggers set to execute on document open or close events, often correlating with embedded payloads or C2 traffic shortly after execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0029](https://attack.mitre.org/detectionstrategies/DET0010#AN0029)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
