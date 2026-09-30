---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0319"
source_url: "https://attack.mitre.org/detectionstrategies/DET0114#AN0319"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0319: Analytic 0319

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0319  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects use of dscl or id/group commands to enumerate local system groups, often by post-exploitation tools or persistence checks.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0319](https://attack.mitre.org/detectionstrategies/DET0114#AN0319)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
