---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0104"
source_url: "https://attack.mitre.org/detectionstrategies/DET0036#AN0104"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0104: Analytic 0104

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0104  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary registers a Windows device to Entra ID or bypasses conditional access by adding device via Intune registration pipeline using stolen credentials.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0104](https://attack.mitre.org/detectionstrategies/DET0036#AN0104)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
