---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1386"
source_url: "https://attack.mitre.org/detectionstrategies/DET0502#AN1386"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1386: Analytic 1386

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1386  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Hidden files via 'chflags hidden' or Apple-specific attributes, LaunchAgents/LaunchDaemons placed in non-standard hidden directories. Defender view: detect command execution modifying file flags and unusual plist creation in hidden paths.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1386](https://attack.mitre.org/detectionstrategies/DET0502#AN1386)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
