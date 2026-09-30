---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1437"
source_url: "https://attack.mitre.org/detectionstrategies/DET0519#AN1437"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1437: Analytic 1437

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1437  
**Platforms:** Office Suite  
**Tactics:** Not specified

## Source description

Malicious VBA macros embedded in base templates like Normal.dotm or Personal.xlsb are automatically loaded and executed at startup. Template path may be hijacked to load a remote or attacker-controlled template via GlobalDotName registry setting.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1437](https://attack.mitre.org/detectionstrategies/DET0519#AN1437)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
