---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1005"
source_url: "https://attack.mitre.org/detectionstrategies/DET0354#AN1005"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1005: Analytic 1005

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1005  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Repeated SSH, VPN, or RDP gateway authentication attempts from external IPs → subsequent successful logon → remote shell or lateral movement activity (e.g., scp/sftp).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1005](https://attack.mitre.org/detectionstrategies/DET0354#AN1005)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
