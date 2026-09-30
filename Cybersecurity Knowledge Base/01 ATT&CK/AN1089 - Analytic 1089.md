---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1089"
source_url: "https://attack.mitre.org/detectionstrategies/DET0386#AN1089"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1089: Analytic 1089

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1089  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Bulk enumeration of cloud user email identities through `Get-Recipient`, `Get-Mailbox`, `Get-User`, or Graph API directory listings by abnormal accounts or suspicious sessions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1089](https://attack.mitre.org/detectionstrategies/DET0386#AN1089)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
