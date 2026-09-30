---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0800"
source_url: "https://attack.mitre.org/detectionstrategies/DET0288#AN0800"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0800: Analytic 0800

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0800  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Correlates suspicious removal or modification of the com.apple.quarantine extended attribute, manipulation of LSFileQuarantineEnabled values in Info.plist, and unexpected process execution of unsigned or non-notarized binaries. Also monitors abnormal trust validation failures in unified logs and unusual activity in QuarantineEvents database entries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0800](https://attack.mitre.org/detectionstrategies/DET0288#AN0800)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
