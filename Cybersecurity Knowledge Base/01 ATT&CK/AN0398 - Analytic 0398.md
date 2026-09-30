---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0398"
source_url: "https://attack.mitre.org/detectionstrategies/DET0141#AN0398"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0398: Analytic 0398

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0398  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Use of `usleep`, `nanosleep`, or `NSTimer` calls in executables or binaries with no GUI interaction, especially followed by disk/network activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0398](https://attack.mitre.org/detectionstrategies/DET0141#AN0398)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
