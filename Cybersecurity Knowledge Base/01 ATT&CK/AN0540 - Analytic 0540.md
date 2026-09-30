---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0540"
source_url: "https://attack.mitre.org/detectionstrategies/DET0189#AN0540"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0540: Analytic 0540

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0540  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of known tools or malware flagged by antivirus, followed by a near-term drop of a similar binary with modified signature and resumed activity (execution, C2, or persistence).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0540](https://attack.mitre.org/detectionstrategies/DET0189#AN0540)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
