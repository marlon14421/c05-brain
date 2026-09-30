---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0467"
source_url: "https://attack.mitre.org/detectionstrategies/DET0165#AN0467"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0467: Analytic 0467

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0467  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects adversary behavior clearing command history via `history -c`, deletion or modification of ~/.bash_history, or manipulation of the HISTFILE environment variable post-login.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0467](https://attack.mitre.org/detectionstrategies/DET0165#AN0467)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
