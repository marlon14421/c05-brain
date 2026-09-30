---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0939"
source_url: "https://attack.mitre.org/detectionstrategies/DET0330#AN0939"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0939: Analytic 0939

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0939  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detection of maintainer scripts (e.g., postinst, preinst) being modified or executed during dpkg or rpm operations. Watch for script content that spawns additional processes or writes outside package scope.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0939](https://attack.mitre.org/detectionstrategies/DET0330#AN0939)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
