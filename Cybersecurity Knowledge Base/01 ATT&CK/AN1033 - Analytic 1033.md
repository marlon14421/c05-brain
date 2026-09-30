---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1033"
source_url: "https://attack.mitre.org/detectionstrategies/DET0366#AN1033"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1033: Analytic 1033

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1033  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects adversary behavior where a file with a benign-looking first extension (e.g., .txt, .jpg) ends with a dangerous second extension (e.g., .exe, .scr), and is subsequently executed. The behavior chain includes file creation with misleading naming and user or system-initiated process execution from the disguised file.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1033](https://attack.mitre.org/detectionstrategies/DET0366#AN1033)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
