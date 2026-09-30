---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0777"
source_url: "https://attack.mitre.org/detectionstrategies/DET0278#AN0777"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0777: Analytic 0777

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0777  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Unexpected firmware image uploads via TFTP/FTP/SCP. Configuration changes modifying boot image pointers. Logs showing boot variable redirection to non-standard images. Anomalous reboots immediately following firmware changes not tied to patch schedules.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0777](https://attack.mitre.org/detectionstrategies/DET0278#AN0777)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
