---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1160"
source_url: "https://attack.mitre.org/detectionstrategies/DET0413#AN1160"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1160: Analytic 1160

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1160  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Programmatic or excessive access to file shares, SharePoint, or database repositories by users not typically interacting with them. This includes abnormal access by privileged accounts, enumeration of large numbers of files, or downloads of sensitive content in bursts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1160](https://attack.mitre.org/detectionstrategies/DET0413#AN1160)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
