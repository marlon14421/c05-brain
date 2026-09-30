---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1556"
source_url: "https://attack.mitre.org/detectionstrategies/DET0563#AN1556"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1556: Analytic 1556

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1556  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection of bash/zsh history suppression via HISTFILE/HISTCONTROL manipulation and absence of ~/.bash_history updates. Observing environment variable changes tied to terminal processes is a strong indicator.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1556](https://attack.mitre.org/detectionstrategies/DET0563#AN1556)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
