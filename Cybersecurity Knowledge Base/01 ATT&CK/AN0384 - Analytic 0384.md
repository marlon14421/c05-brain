---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0384"
source_url: "https://attack.mitre.org/detectionstrategies/DET0137#AN0384"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0384: Analytic 0384

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0384  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unusual direct disk access attempts (e.g., use of \\.\PhysicalDrive notation), abnormal writes to MBR/boot sectors, and installation of kernel drivers that grant raw disk access. Correlate anomalous process creation with disk modification attempts and driver loads.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0384](https://attack.mitre.org/detectionstrategies/DET0137#AN0384)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
