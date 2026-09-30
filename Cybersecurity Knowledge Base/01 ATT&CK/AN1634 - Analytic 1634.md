---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1634"
source_url: "https://attack.mitre.org/detectionstrategies/DET0595#AN1634"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1634: Analytic 1634

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1634  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects kernel- or user-space exploitation attempts targeting auditd, AV daemons, or security monitoring agents. Defender observation includes unexpected segfaults, privilege escalation attempts from low-privileged processes, or modifications to security binaries. Correlates exploitation attempts with subsequent gaps in logging or terminated processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1634](https://attack.mitre.org/detectionstrategies/DET0595#AN1634)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
