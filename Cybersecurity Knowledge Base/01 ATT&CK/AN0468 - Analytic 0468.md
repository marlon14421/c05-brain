---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0468"
source_url: "https://attack.mitre.org/detectionstrategies/DET0165#AN0468"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0468: Analytic 0468

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0468  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects adversary clearing shell history using `history -c` or deleting/altering ~/.zsh_history or ~/.bash_history. Focus on sessions with missing or wiped history.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0468](https://attack.mitre.org/detectionstrategies/DET0165#AN0468)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
