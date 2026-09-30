---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1082"
source_url: "https://attack.mitre.org/detectionstrategies/DET0384#AN1082"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1082: Analytic 1082

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1082  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Identifies use of sh/bash/zsh in suspicious context, such as user scripts launched from non-standard apps (e.g., Preview.app), embedded in LaunchDaemons, or executed outside Terminal.app. Looks for misuse in Automator, LaunchAgents, or NSAppleScript-executed shell.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1082](https://attack.mitre.org/detectionstrategies/DET0384#AN1082)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
