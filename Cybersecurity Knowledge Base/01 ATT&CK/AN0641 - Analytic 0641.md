---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0641"
source_url: "https://attack.mitre.org/detectionstrategies/DET0229#AN0641"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0641: Analytic 0641

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0641  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Enumeration of global address lists or email account metadata via PowerShell cmdlets (e.g., Get-GlobalAddressList) or MAPI/RPC from non-admin, non-mailserver systems.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0641](https://attack.mitre.org/detectionstrategies/DET0229#AN0641)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
