---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1577"
source_url: "https://attack.mitre.org/detectionstrategies/DET0571#AN1577"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1577: Analytic 1577

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1577  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects creation or modification of `LaunchDaemon` or `LaunchAgent` plist files under `/Library/LaunchDaemons/`, `~/Library/LaunchAgents/`, or similar. Monitors execution of `launchctl`, property list edits, and file permission changes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1577](https://attack.mitre.org/detectionstrategies/DET0571#AN1577)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
