---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0013"
source_url: "https://attack.mitre.org/detectionstrategies/DET0005#AN0013"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0013: Analytic 0013

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0013  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Execution of renamed or relocated native macOS utilities with uncommon names or non-default paths (e.g., renamed `osascript`, `bash`, or `curl`).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0013](https://attack.mitre.org/detectionstrategies/DET0005#AN0013)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
