---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1116"
source_url: "https://attack.mitre.org/detectionstrategies/DET0398#AN1116"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1116: Analytic 1116

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1116  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Office-based persistence via Office template macros, Outlook forms/rules/homepage, or registry-persistent scripts. Adversary modifies registry keys or Office application directories to load malicious scripts at startup.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1116](https://attack.mitre.org/detectionstrategies/DET0398#AN1116)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
