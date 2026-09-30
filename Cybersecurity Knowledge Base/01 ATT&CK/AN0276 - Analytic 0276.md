---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0276"
source_url: "https://attack.mitre.org/detectionstrategies/DET0099#AN0276"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0276: Analytic 0276

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0276  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Unauthorized firmware uploads to routers, switches, or firewalls via TFTP/FTP/SCP. Logs showing boot variable or startup image path changes redirecting to non-standard firmware images. Abnormal reboots or firmware rollback attempts following configuration modification events.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0276](https://attack.mitre.org/detectionstrategies/DET0099#AN0276)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
