---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0757"
source_url: "https://attack.mitre.org/detectionstrategies/DET0271#AN0757"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0757: Analytic 0757

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0757  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects anomalous process access to LSASS on domain controllers, suspicious module loads of authentication DLLs, and registry or file modifications indicative of Skeleton Key–style patching. Correlates LSASS access attempts with subsequent abnormal logon activity patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0757](https://attack.mitre.org/detectionstrategies/DET0271#AN0757)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
