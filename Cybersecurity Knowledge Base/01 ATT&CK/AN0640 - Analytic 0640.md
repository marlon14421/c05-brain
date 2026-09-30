---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0640"
source_url: "https://attack.mitre.org/detectionstrategies/DET0228#AN0640"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0640: Analytic 0640

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0640  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

CLI-based or API-based network call from the hypervisor to external staging host, shortly followed by a connection to a second external IP by a spawned process or scheduled task.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0640](https://attack.mitre.org/detectionstrategies/DET0228#AN0640)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
