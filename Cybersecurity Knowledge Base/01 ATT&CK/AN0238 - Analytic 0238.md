---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0238"
source_url: "https://attack.mitre.org/detectionstrategies/DET0087#AN0238"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0238: Analytic 0238

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0238  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detection of suspicious use of shell utilities or scripts that decode or decrypt a payload and execute it without writing to disk.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0238](https://attack.mitre.org/detectionstrategies/DET0087#AN0238)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
