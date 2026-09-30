---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1291"
source_url: "https://attack.mitre.org/detectionstrategies/DET0468#AN1291"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1291: Analytic 1291

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1291  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects rogue DHCP activity by monitoring syslog for dhclient messages assigning unauthorized DNS/gateway values. Packet capture or IDS can detect multiple competing DHCP OFFERs from non-authorized servers.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1291](https://attack.mitre.org/detectionstrategies/DET0468#AN1291)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
