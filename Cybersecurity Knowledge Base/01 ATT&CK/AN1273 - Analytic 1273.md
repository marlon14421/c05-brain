---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1273"
source_url: "https://attack.mitre.org/detectionstrategies/DET0461#AN1273"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1273: Analytic 1273

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1273  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Hidden file system use through APFS containers or custom plist configuration. Defender view: anomalous use of hdiutil or diskutil to attach hidden partitions, modification of plist entries tied to system volumes, or suspicious raw disk access.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1273](https://attack.mitre.org/detectionstrategies/DET0461#AN1273)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
