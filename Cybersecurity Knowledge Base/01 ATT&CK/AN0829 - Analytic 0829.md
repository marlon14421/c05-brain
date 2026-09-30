---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0829"
source_url: "https://attack.mitre.org/detectionstrategies/DET0297#AN0829"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0829: Analytic 0829

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0829  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Abnormal invocation of diskutil or asr that modifies partition tables or initializes raw devices. Monitor for IOKit system calls targeting disk headers or EFI boot sectors, correlated with elevated privileges.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0829](https://attack.mitre.org/detectionstrategies/DET0297#AN0829)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
