---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0722"
source_url: "https://attack.mitre.org/detectionstrategies/DET0260#AN0722"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0722: Analytic 0722

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0722  
**Platforms:** SaaS  
**Tactics:** Not specified

## Source description

SaaS platforms may show forged credentials as unusual API keys, tokens, or session cookies being used without corresponding authentication. Correlated patterns include simultaneous valid sessions from multiple geographies, unusual API calls with new tokens, or bypass of expected MFA enforcement.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0722](https://attack.mitre.org/detectionstrategies/DET0260#AN0722)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
