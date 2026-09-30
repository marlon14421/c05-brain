---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0278"
source_url: "https://attack.mitre.org/detectionstrategies/DET0101#AN0278"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0278: Analytic 0278

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0278  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects execution of Lua interpreters or scripts (.lua), especially when correlated with suspicious parent processes or file drop events, indicating malicious use of embedded scripting.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0278](https://attack.mitre.org/detectionstrategies/DET0101#AN0278)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
