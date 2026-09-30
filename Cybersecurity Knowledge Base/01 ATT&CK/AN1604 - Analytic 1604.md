---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1604"
source_url: "https://attack.mitre.org/detectionstrategies/DET0583#AN1604"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1604: Analytic 1604

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1604  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary uses built-in OS tools or API calls to create local or domain accounts for persistence or lateral movement. Tools such as 'net user', PowerShell, or MMC snap-ins may be used. Detection focuses on Event ID 4720 paired with process lineage and user context.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1604](https://attack.mitre.org/detectionstrategies/DET0583#AN1604)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
