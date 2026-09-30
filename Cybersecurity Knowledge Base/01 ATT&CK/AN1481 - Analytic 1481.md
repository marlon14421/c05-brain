---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1481"
source_url: "https://attack.mitre.org/detectionstrategies/DET0537#AN1481"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1481: Analytic 1481

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1481  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

1) Package manager or curl/wget installs/upgrades from non-approved repos or unsigned packages; 2) new ELF written into PATH directories or replacement of existing binaries/libraries; 3) first run leads to unexpected child processes or outbound connections.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1481](https://attack.mitre.org/detectionstrategies/DET0537#AN1481)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
