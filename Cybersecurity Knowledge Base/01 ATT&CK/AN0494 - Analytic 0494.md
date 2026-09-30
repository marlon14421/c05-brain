---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0494"
source_url: "https://attack.mitre.org/detectionstrategies/DET0174#AN0494"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0494: Analytic 0494

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0494  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects exploitation of authentication daemons or PAM modules. Defender perspective includes failed or anomalous PAM authentications, abnormal segfaults in authentication services, and exploitation attempts followed by successful unauthorized logins. Correlation identifies memory corruption, replay attempts, and privilege escalation tied to credential services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0494](https://attack.mitre.org/detectionstrategies/DET0174#AN0494)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
