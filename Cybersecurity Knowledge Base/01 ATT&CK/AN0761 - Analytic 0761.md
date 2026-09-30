---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0761"
source_url: "https://attack.mitre.org/detectionstrategies/DET0273#AN0761"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0761: Analytic 0761

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0761  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Applications or launchd jobs initiating encrypted TLS traffic to rare external hosts. Defender observes unified logs showing ssl/TLS API calls by processes not baseline-approved, and payload entropy suggesting encrypted C2 sessions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0761](https://attack.mitre.org/detectionstrategies/DET0273#AN0761)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
