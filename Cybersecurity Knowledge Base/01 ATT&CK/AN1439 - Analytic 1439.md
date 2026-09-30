---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1439"
source_url: "https://attack.mitre.org/detectionstrategies/DET0520#AN1439"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1439: Analytic 1439

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1439  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects adversary clearing log files on macOS by correlating calls to shell utilities (e.g., echo >, rm, truncate) targeting files in /var/log/ with unusual context (non-administrative users or abnormal process lineage).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1439](https://attack.mitre.org/detectionstrategies/DET0520#AN1439)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
