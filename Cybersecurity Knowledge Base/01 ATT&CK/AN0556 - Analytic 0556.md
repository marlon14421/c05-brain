---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0556"
source_url: "https://attack.mitre.org/detectionstrategies/DET0193#AN0556"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0556: Analytic 0556

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0556  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detect suspicious file creation, modification, or deletion in stored data directories (e.g., `/var/lib/mysql/`, `/var/log/`, mail spools). Identify shell commands interacting directly with structured data files instead of legitimate database utilities.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0556](https://attack.mitre.org/detectionstrategies/DET0193#AN0556)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
