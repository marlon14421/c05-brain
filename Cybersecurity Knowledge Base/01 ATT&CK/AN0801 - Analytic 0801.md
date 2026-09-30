---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0801"
source_url: "https://attack.mitre.org/detectionstrategies/DET0289#AN0801"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0801: Analytic 0801

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0801  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Cloud API events where logging services are stopped, deleted, or modified in a way that disables audit visibility. Defender view: unauthorized StopLogging, DeleteTrail, or UpdateSink operations correlated with privileged user activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0801](https://attack.mitre.org/detectionstrategies/DET0289#AN0801)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
