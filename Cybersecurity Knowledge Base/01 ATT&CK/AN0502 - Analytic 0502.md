---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0502"
source_url: "https://attack.mitre.org/detectionstrategies/DET0177#AN0502"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0502: Analytic 0502

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0502  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary uses a tool like Ruler to configure a malicious Outlook folder Home Page that loads a remote or embedded HTML payload upon folder interaction. Execution chain begins with Outlook launching, a specific folder being accessed, and a suspicious child process being spawned or COM-based execution invoked.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0502](https://attack.mitre.org/detectionstrategies/DET0177#AN0502)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
