---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0290"
source_url: "https://attack.mitre.org/detectionstrategies/DET0104#AN0290"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0290: Analytic 0290

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0290  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Detects suspicious configuration changes in IdP authentication flows such as enabling reversible password encryption, MFA bypass, or policy weakening. Correlates policy modification events with unusual administrative activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0290](https://attack.mitre.org/detectionstrategies/DET0104#AN0290)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
