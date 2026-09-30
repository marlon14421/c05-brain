---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0216"
source_url: "https://attack.mitre.org/detectionstrategies/DET0079#AN0216"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0216: Analytic 0216

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0216  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of anomalous RDP or remote service session activity where a logon session is hijacked rather than newly created. Indicators include mismatched user credentials vs. active session tokens, service session takeovers without corresponding successful logon events, or RDP shadowing activity without user consent.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0216](https://attack.mitre.org/detectionstrategies/DET0079#AN0216)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
