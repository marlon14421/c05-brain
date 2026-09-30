---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0173"
source_url: "https://attack.mitre.org/detectionstrategies/DET0063#AN0173"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0173: Analytic 0173

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0173  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects native Python or framework-based execution from Terminal, embedded apps, or launchd jobs. Flags network calls, persistence writes, or system enumeration after Python launch.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0173](https://attack.mitre.org/detectionstrategies/DET0063#AN0173)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
