---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1609"
source_url: "https://attack.mitre.org/detectionstrategies/DET0584#AN1609"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1609: Analytic 1609

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1609  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Unexpected creation or modification of files with `com.apple.ResourceFork` extended attributes containing unusually large or non-standard data. Defender perspective: detection of resource forks in contexts where they are uncommon, especially when paired with process execution or network activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1609](https://attack.mitre.org/detectionstrategies/DET0584#AN1609)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
