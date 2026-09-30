---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0323"
source_url: "https://attack.mitre.org/detectionstrategies/DET0116#AN0323"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0323: Analytic 0323

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0323  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Abuse of safe mode via BCD modification, boot configuration utilities (bcdedit.exe, bootcfg.exe), and registry persistence under SafeBoot keys. Defender view: suspicious boot configuration changes correlated with registry edits that enable adversary persistence or disable defenses.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0323](https://attack.mitre.org/detectionstrategies/DET0116#AN0323)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
