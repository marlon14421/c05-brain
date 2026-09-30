---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0911"
source_url: "https://attack.mitre.org/detectionstrategies/DET0321#AN0911"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0911: Analytic 0911

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0911  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Execution of virtualization binaries (Parallels, VMware Fusion, VirtualBox) with arguments to hide UI. File monitoring for plist modifications indicating hidden virtualization behavior. Defender perspective: tracking process lineage and file modifications in system configs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0911](https://attack.mitre.org/detectionstrategies/DET0321#AN0911)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
