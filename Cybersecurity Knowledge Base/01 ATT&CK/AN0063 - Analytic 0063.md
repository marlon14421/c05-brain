---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0063"
source_url: "https://attack.mitre.org/detectionstrategies/DET0021#AN0063"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0063: Analytic 0063

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0063  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Use of launchctl to stop services or kill critical background processes (e.g., securityd, com.apple.*), typically followed by command-line tools like rm or diskutil. Behavioral chain: Terminal or remote shell + launchctl bootout/disable + process termination + follow-on modification.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0063](https://attack.mitre.org/detectionstrategies/DET0021#AN0063)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
