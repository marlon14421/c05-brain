---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1272"
source_url: "https://attack.mitre.org/detectionstrategies/DET0461#AN1272"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1272: Analytic 1272

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1272  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Unusual mounting of loopback or pseudo file systems not aligned with legitimate administrative activity. Defender view: monitoring auditd and syslog for mount commands involving suspicious mount points, reserved blocks, or device mappings indicative of hidden partitions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1272](https://attack.mitre.org/detectionstrategies/DET0461#AN1272)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
