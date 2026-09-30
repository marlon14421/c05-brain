---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1175"
source_url: "https://attack.mitre.org/detectionstrategies/DET0417#AN1175"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1175: Analytic 1175

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1175  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detect execution of system utilities (systemctl, systemd-inhibit, systemdsleep) modifying sleep or hibernate behavior. Abnormal edits to system configuration files (e.g., /etc/systemd/sleep.conf) should be correlated with process execution to identify persistence techniques.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1175](https://attack.mitre.org/detectionstrategies/DET0417#AN1175)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
