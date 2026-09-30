---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2044"
source_url: "https://attack.mitre.org/detectionstrategies/DET0497#AN2044"
created: "2026-04-20"
modified: "2026-05-12"
---
# AN2044: Analytic 2044

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2044  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects esxcli commands disabling syslog, firewall, lockdown mode, or stopping hostd/vpxa; correlates command execution with reduced forwarding activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2044](https://attack.mitre.org/detectionstrategies/DET0497#AN2044)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
