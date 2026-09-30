---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0882"
source_url: "https://attack.mitre.org/detectionstrategies/DET0316#AN0882"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0882: Analytic 0882

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0882  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes attempting raw disk access via \\.\PhysicalDrive paths, abnormal file I/O to MBR/boot sectors, or loading of third-party drivers (e.g., RawDisk) that enable disk overwrite. Correlate process creation, privilege usage, and disk modification events within a short time window.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0882](https://attack.mitre.org/detectionstrategies/DET0316#AN0882)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
