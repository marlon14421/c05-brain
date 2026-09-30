---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0796"
source_url: "https://attack.mitre.org/detectionstrategies/DET0286#AN0796"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0796: Analytic 0796

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0796  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Monitor Office Suite applications (Outlook, Word mail merge, Excel macros) for abnormal automated message sending, especially when macros or scripts trigger email delivery. Detect patterns of impersonation language (urgent, payment, executive request) combined with anomalous execution of Office macros.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0796](https://attack.mitre.org/detectionstrategies/DET0286#AN0796)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
