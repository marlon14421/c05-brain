---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0461"
source_url: "https://attack.mitre.org/detectionstrategies/DET0161#AN0461"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0461: Analytic 0461

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0461  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Chain: (1) privileged CLI sessions run read-only commands that dump AAA/password policies (e.g., `show aaa`, `show password-policy`); (2) same account changes AAA or user DB shortly after. Use network device AAA/command accounting or syslog.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0461](https://attack.mitre.org/detectionstrategies/DET0161#AN0461)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
