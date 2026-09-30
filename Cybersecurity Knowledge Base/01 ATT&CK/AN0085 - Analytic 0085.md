---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0085"
source_url: "https://attack.mitre.org/detectionstrategies/DET0029#AN0085"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0085: Analytic 0085

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0085  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary uses a tool like Ruler to insert a malicious custom form into the user's Outlook mailbox. The form is designed to auto-execute on Outlook startup or on receipt of a specially crafted email. This results in child processes launched from outlook.exe and possibly network connections or payload loading.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0085](https://attack.mitre.org/detectionstrategies/DET0029#AN0085)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
