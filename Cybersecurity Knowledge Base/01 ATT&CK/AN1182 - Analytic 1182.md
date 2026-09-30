---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1182"
source_url: "https://attack.mitre.org/detectionstrategies/DET0420#AN1182"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1182: Analytic 1182

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1182  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Process execution that probes user activity artifacts (e.g., desktop files, registry history) following recent user login/unlock events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1182](https://attack.mitre.org/detectionstrategies/DET0420#AN1182)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
