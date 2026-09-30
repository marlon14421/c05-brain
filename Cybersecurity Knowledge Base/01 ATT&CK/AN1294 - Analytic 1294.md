---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1294"
source_url: "https://attack.mitre.org/detectionstrategies/DET0470#AN1294"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1294: Analytic 1294

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1294  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Untrusted processes creating outbound TLS/HTTPS connections with malformed certificates or header fields, often mismatched with target service behavior. Detects protocol impersonation attempts via traffic metadata analysis and host process lineage.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1294](https://attack.mitre.org/detectionstrategies/DET0470#AN1294)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
