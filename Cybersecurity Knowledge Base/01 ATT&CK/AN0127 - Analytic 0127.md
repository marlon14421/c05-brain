---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0127"
source_url: "https://attack.mitre.org/detectionstrategies/DET0046#AN0127"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0127: Analytic 0127

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0127  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of discovery commands or API calls for virtualization artifacts (e.g., registry keys, device drivers, services), sleep/skipped execution behavior, or sandbox evasion DLLs before payload deployment.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0127](https://attack.mitre.org/detectionstrategies/DET0046#AN0127)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
