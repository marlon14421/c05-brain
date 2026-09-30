---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0917"
source_url: "https://attack.mitre.org/detectionstrategies/DET0323#AN0917"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0917: Analytic 0917

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0917  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detection of suspicious use of ioctl/sysfs calls to access device firmware, unexpected flashing tools execution, and anomalous firmware checksums logged by SMART or kernel audit mechanisms.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0917](https://attack.mitre.org/detectionstrategies/DET0323#AN0917)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
