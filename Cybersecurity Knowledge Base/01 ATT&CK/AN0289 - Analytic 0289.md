---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0289"
source_url: "https://attack.mitre.org/detectionstrategies/DET0104#AN0289"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0289: Analytic 0289

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0289  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects unauthorized additions or changes to /Library/Security/SecurityAgentPlugins and suspicious process activity attempting to hook authentication APIs. Correlates file modifications with abnormal plugin loads in authentication flows.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0289](https://attack.mitre.org/detectionstrategies/DET0104#AN0289)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
