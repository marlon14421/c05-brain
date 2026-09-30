---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0134"
source_url: "https://attack.mitre.org/detectionstrategies/DET0049#AN0134"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0134: Analytic 0134

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0134  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects deletion or overwriting of logs/configs that store SSH or proxy activity, such as /var/log/auth.log or custom .bash_history clearing tied to SSH sessions or firewall rule changes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0134](https://attack.mitre.org/detectionstrategies/DET0049#AN0134)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
