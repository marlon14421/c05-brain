---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0712"
source_url: "https://attack.mitre.org/detectionstrategies/DET0257#AN0712"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0712: Analytic 0712

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0712  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects extraction or mounting of container/archive files (e.g., .iso, .vhd, .zip) that originated from the Internet but whose contained files lack Zone.Identifier MOTW tagging. Correlates file creation metadata with subsequent execution of unsigned or untrusted binaries launched outside SmartScreen or Protected View.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0712](https://attack.mitre.org/detectionstrategies/DET0257#AN0712)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
