---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0371"
source_url: "https://attack.mitre.org/detectionstrategies/DET0131#AN0371"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0371: Analytic 0371

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0371  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects outbound traffic from hostd/vpxa or guest VM interfaces using unauthorized protocols such as FTP, HTTP POST bursts, or long-lived DNS tunnels.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0371](https://attack.mitre.org/detectionstrategies/DET0131#AN0371)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
