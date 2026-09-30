---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0543"
source_url: "https://attack.mitre.org/detectionstrategies/DET0190#AN0543"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0543: Analytic 0543

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0543  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects registry and Group Policy modifications that disable or weaken MFA, suspicious PowerShell usage modifying MFA-related attributes, and anomalous login sessions succeeding without expected MFA challenge.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0543](https://attack.mitre.org/detectionstrategies/DET0190#AN0543)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
