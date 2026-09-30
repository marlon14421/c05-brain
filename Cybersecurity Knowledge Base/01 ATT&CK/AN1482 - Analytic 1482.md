---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1482"
source_url: "https://attack.mitre.org/detectionstrategies/DET0537#AN1482"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1482: Analytic 1482

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1482  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

1) pkg/notarization installs from atypical sources or with Gatekeeper/AMFI warnings; 2) new Mach-O written into /Applications or ~/Library paths or substitution of signed components; 3) first run from installer spawns unsigned children or exfil.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1482](https://attack.mitre.org/detectionstrategies/DET0537#AN1482)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
