---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0856"
source_url: "https://attack.mitre.org/detectionstrategies/DET0307#AN0856"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0856: Analytic 0856

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0856  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Correlated file access to insecure credential files (e.g., *.env, *.xml, *.ps1) followed by suspicious process execution or authentication using retrieved credentials. Detected through Sysmon logs and Windows Security Event logs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0856](https://attack.mitre.org/detectionstrategies/DET0307#AN0856)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
