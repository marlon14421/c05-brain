---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0563"
source_url: "https://attack.mitre.org/detectionstrategies/DET0195#AN0563"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0563: Analytic 0563

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0563  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

CLI-based execution of interface and routing discovery commands (e.g., `show ip interface`, `show arp`, `show route`) over Telnet, SSH, or console.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0563](https://attack.mitre.org/detectionstrategies/DET0195#AN0563)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
