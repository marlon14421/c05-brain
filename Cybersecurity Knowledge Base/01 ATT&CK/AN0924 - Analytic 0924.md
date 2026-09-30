---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0924"
source_url: "https://attack.mitre.org/detectionstrategies/DET0325#AN0924"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0924: Analytic 0924

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0924  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

AppleScript or terminal sessions launch tools (`curl`, `nc`, `ssh`) to external IPs not commonly accessed. Outbound connections are made by LaunchAgents/LaunchDaemons, often masquerading as system services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0924](https://attack.mitre.org/detectionstrategies/DET0325#AN0924)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
