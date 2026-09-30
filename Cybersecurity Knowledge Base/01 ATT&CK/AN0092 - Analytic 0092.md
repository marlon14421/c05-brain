---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0092"
source_url: "https://attack.mitre.org/detectionstrategies/DET0032#AN0092"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0092: Analytic 0092

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0092  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Creation of files or directories with a leading '.' in privileged directories (/etc, /var, /usr/bin). Defender view: monitoring auditd logs for file creations where name begins with '.' and correlated with unusual user/process context.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0092](https://attack.mitre.org/detectionstrategies/DET0032#AN0092)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
