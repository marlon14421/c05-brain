---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1444"
source_url: "https://attack.mitre.org/detectionstrategies/DET0522#AN1444"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1444: Analytic 1444

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1444  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects suspicious access to SSSD secrets database and Kerberos key material indicating ticket theft or replay attempts. Correlates anomalous file access with unusual Kerberos service ticket requests.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1444](https://attack.mitre.org/detectionstrategies/DET0522#AN1444)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
