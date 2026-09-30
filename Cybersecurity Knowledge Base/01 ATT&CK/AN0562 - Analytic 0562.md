---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0562"
source_url: "https://attack.mitre.org/detectionstrategies/DET0195#AN0562"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0562: Analytic 0562

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0562  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Use of `esxcli network` commands (e.g., `esxcli network nic list`, `esxcli network ip interface ipv4 get`) via SSH or hostd to enumerate adapter and IP information.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0562](https://attack.mitre.org/detectionstrategies/DET0195#AN0562)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
