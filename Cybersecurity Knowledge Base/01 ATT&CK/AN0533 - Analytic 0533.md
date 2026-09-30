---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0533"
source_url: "https://attack.mitre.org/detectionstrategies/DET0186#AN0533"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0533: Analytic 0533

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0533  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Use of pbpaste, AppleScript, or third-party automation frameworks (e.g., Automator) to collect clipboard or file content in bursts. Observable via unified logs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0533](https://attack.mitre.org/detectionstrategies/DET0186#AN0533)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
