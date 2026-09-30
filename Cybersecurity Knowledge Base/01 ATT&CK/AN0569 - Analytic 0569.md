---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0569"
source_url: "https://attack.mitre.org/detectionstrategies/DET0197#AN0569"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0569: Analytic 0569

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0569  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

A process opens/reads /dev/video* (V4L2), performs ioctl/read loops, writes large/continuous video artifacts to disk, and/or quickly establishes outbound connections for exfiltration.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0569](https://attack.mitre.org/detectionstrategies/DET0197#AN0569)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
