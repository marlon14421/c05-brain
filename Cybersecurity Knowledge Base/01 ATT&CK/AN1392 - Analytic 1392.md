---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1392"
source_url: "https://attack.mitre.org/detectionstrategies/DET0503#AN1392"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1392: Analytic 1392

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1392  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects unexpected encrypted egress traffic from management services (e.g., hostd) or guest VMs utilizing symmetric encryption without traditional protocols (e.g., FTP with embedded AES ciphertext).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1392](https://attack.mitre.org/detectionstrategies/DET0503#AN1392)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
