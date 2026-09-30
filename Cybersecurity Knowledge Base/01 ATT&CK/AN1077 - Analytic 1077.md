---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1077"
source_url: "https://attack.mitre.org/detectionstrategies/DET0383#AN1077"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1077: Analytic 1077

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1077  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects adversary behavior where a newly created or renamed user account closely resembles existing service or administrator accounts to blend in and avoid detection. Common patterns include prefix/suffix modifications, homoglyphs, or use of names like 'admin1', 'adm1n', or 'backup_help'.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1077](https://attack.mitre.org/detectionstrategies/DET0383#AN1077)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
