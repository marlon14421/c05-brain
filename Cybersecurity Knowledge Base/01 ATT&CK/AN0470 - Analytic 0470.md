---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0470"
source_url: "https://attack.mitre.org/detectionstrategies/DET0165#AN0470"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0470: Analytic 0470

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0470  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects modification or truncation of `/var/log/shell.log` used to persist ESXi shell command history. Especially suspicious shortly after login or config changes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0470](https://attack.mitre.org/detectionstrategies/DET0165#AN0470)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
