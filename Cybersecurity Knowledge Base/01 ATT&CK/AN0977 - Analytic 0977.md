---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0977"
source_url: "https://attack.mitre.org/detectionstrategies/DET0345#AN0977"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0977: Analytic 0977

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0977  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detect execution of `/usr/libexec/security_authtrampoline` or use of AuthorizationExecuteWithPrivileges API, and monitor process lineage for unusual launches of GUI apps with escalated privileges.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0977](https://attack.mitre.org/detectionstrategies/DET0345#AN0977)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
