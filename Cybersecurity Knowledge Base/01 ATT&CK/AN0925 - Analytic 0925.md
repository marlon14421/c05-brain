---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0925"
source_url: "https://attack.mitre.org/detectionstrategies/DET0325#AN0925"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0925: Analytic 0925

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0925  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

ESXi shell or guest VM tools initiate external connections via scripted traffic forwarding to Internet-based proxies. Detected by firewall or shell audit logs showing outbound connection spikes from hypervisor or guest VM to remote proxy nodes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0925](https://attack.mitre.org/detectionstrategies/DET0325#AN0925)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
