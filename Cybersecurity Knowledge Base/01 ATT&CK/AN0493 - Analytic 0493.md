---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0493"
source_url: "https://attack.mitre.org/detectionstrategies/DET0174#AN0493"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0493: Analytic 0493

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0493  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects adversary exploitation of authentication mechanisms or credential validation processes. Defender perspective includes forged Kerberos tickets (e.g., MS14-068), abnormal LSASS memory access, replayed authentication attempts, and unexpected crashes of authentication services. Multi-event correlation ties exploitation attempts to abnormal process creation, service instability, and suspicious authentication events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0493](https://attack.mitre.org/detectionstrategies/DET0174#AN0493)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
