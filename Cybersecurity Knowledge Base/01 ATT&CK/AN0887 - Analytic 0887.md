---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0887"
source_url: "https://attack.mitre.org/detectionstrategies/DET0317#AN0887"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0887: Analytic 0887

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0887  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Execution of commands that stop or kill processes associated with logging or security daemons (auditd, syslog, falco). Detect modifications to iptables or disabling SELinux/AppArmor enforcement. Correlate sudo/root context with abrupt service halts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0887](https://attack.mitre.org/detectionstrategies/DET0317#AN0887)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
