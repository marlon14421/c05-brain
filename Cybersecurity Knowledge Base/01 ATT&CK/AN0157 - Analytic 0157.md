---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0157"
source_url: "https://attack.mitre.org/detectionstrategies/DET0057#AN0157"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0157: Analytic 0157

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0157  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects adversaries attempting to attach debuggers or memory dump utilities to credential storage daemons analogous to macOS `securityd`. Observes ptrace syscalls, /proc/ /mem access, or gcore dumps against sensitive processes. Correlates anomalies with privilege escalation or credential dumping attempts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0157](https://attack.mitre.org/detectionstrategies/DET0057#AN0157)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
