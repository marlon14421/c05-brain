---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0890"
source_url: "https://attack.mitre.org/detectionstrategies/DET0317#AN0890"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0890: Analytic 0890

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0890  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Unusual ESXi shell commands disabling syslog forwarding or stopping hostd/vpxa daemons. Detect modifications to firewall rules on ESXi host or disabling of lockdown mode.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0890](https://attack.mitre.org/detectionstrategies/DET0317#AN0890)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
