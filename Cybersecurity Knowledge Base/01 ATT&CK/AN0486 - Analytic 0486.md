---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0486"
source_url: "https://attack.mitre.org/detectionstrategies/DET0171#AN0486"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0486: Analytic 0486

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0486  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Forged cookies on macOS may show up as abnormal access to Safari/Chrome cookie databases in ~/Library/Cookies, combined with unexpected logon sessions authenticated by those cookies. Unified Logs may show cookie injection events or abnormal access patterns to Keychain when linked to browser authentication flows.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0486](https://attack.mitre.org/detectionstrategies/DET0171#AN0486)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
