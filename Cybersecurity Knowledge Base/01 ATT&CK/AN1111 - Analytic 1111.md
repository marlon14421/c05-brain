---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1111"
source_url: "https://attack.mitre.org/detectionstrategies/DET0395#AN1111"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1111: Analytic 1111

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1111  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects abuse of AuthorizationExecuteWithPrivileges API to gain elevated privileges via user credential prompts, typically through invocation of /usr/libexec/security_authtrampoline. Detection involves correlation of API usage, binary reputation, and prompt context.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1111](https://attack.mitre.org/detectionstrategies/DET0395#AN1111)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
