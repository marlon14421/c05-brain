---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0497"
source_url: "https://attack.mitre.org/detectionstrategies/DET0175#AN0497"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0497: Analytic 0497

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0497  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detection of anomalous ROMMON image changes or upgrades, unexpected reboots following firmware updates, and unauthorized use of firmware upgrade commands or TFTP transfers. Correlation of config modification, privilege escalation, and boot cycle anomalies provides visibility into ROMMON tampering attempts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0497](https://attack.mitre.org/detectionstrategies/DET0175#AN0497)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
