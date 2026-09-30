---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0067"
source_url: "https://attack.mitre.org/detectionstrategies/DET0023#AN0067"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0067: Analytic 0067

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0067  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Correlates ELF file execution with high-entropy writable memory segments and self-modifying code patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0067](https://attack.mitre.org/detectionstrategies/DET0023#AN0067)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
