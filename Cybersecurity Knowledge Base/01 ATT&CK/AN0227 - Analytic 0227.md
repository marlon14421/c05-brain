---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0227"
source_url: "https://attack.mitre.org/detectionstrategies/DET0081#AN0227"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0227: Analytic 0227

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0227  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Execution of trusted system binaries (e.g., `split`, `tee`, `bash`, `env`) used in uncommon sequences or chained behaviors to execute malicious payloads or perform actions inconsistent with normal system or script behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0227](https://attack.mitre.org/detectionstrategies/DET0081#AN0227)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
