---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0740"
source_url: "https://attack.mitre.org/detectionstrategies/DET0266#AN0740"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0740: Analytic 0740

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0740  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Detects Exchange Online or on-prem transport rule changes (e.g., header stripping) and mailbox export cleanup via `Remove-MailboxExportRequest`, as well as admin actions via Exchange PowerShell sessions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0740](https://attack.mitre.org/detectionstrategies/DET0266#AN0740)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
