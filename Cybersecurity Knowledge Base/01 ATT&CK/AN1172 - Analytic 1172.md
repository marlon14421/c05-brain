---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1172"
source_url: "https://attack.mitre.org/detectionstrategies/DET0416#AN1172"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1172: Analytic 1172

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1172  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects file movement or outbound TFTP/FTP transfers from ESXi host initiated via shell commands or injected scripts, particularly from scratch partitions or /tmp.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1172](https://attack.mitre.org/detectionstrategies/DET0416#AN1172)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
