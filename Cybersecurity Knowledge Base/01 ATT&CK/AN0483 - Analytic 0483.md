---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0483"
source_url: "https://attack.mitre.org/detectionstrategies/DET0171#AN0483"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0483: Analytic 0483

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0483  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Forged cookies in IaaS environments may appear as authentication attempts that bypass MFA, leveraging AssumeRole or session APIs with cookies that were never legitimately issued. Defenders should correlate cloud logs for cookie-based sessions without prior valid authentication, often followed by resource access from unfamiliar IP addresses.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0483](https://attack.mitre.org/detectionstrategies/DET0171#AN0483)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
