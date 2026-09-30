---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0837"
source_url: "https://attack.mitre.org/detectionstrategies/DET0299#AN0837"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0837: Analytic 0837

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0837  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

ESXi hypervisor permission modification behavioral chain: (1) SSH access to ESXi host, (2) chmod/chown execution on VMFS datastore files or system configuration, (3) Modification of VM configuration files (.vmx) or virtual disk permissions, (4) Hostd service log correlation, (5) vCenter permission change events if centrally managed

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0837](https://attack.mitre.org/detectionstrategies/DET0299#AN0837)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
