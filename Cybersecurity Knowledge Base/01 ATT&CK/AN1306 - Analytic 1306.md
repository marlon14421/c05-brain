---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1306"
source_url: "https://attack.mitre.org/detectionstrategies/DET0474#AN1306"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1306: Analytic 1306

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1306  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Linux environmental keying behavioral chain: (1) System information gathering through native commands (uname, hostname, id, whoami, ifconfig/ip) and file system enumeration, (2) Network configuration discovery (route tables, DNS settings, network interfaces), (3) Filesystem and mount point analysis for target-specific directories or devices, (4) Process and service enumeration to identify target-specific software, (5) Cryptographic library usage correlation with collected environmental data, (6) Payload execution following successful environmental validation

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1306](https://attack.mitre.org/detectionstrategies/DET0474#AN1306)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
