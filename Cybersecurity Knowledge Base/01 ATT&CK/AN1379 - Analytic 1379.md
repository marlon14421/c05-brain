---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1379"
source_url: "https://attack.mitre.org/detectionstrategies/DET0499#AN1379"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1379: Analytic 1379

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1379  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Outbound traffic from host management services or guest-to-host interactions over unusual interfaces (e.g., backdoor API endpoints or external VPN tunnels).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1379](https://attack.mitre.org/detectionstrategies/DET0499#AN1379)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
