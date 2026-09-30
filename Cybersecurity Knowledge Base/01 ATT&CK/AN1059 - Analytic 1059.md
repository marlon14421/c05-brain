---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1059"
source_url: "https://attack.mitre.org/detectionstrategies/DET0376#AN1059"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1059: Analytic 1059

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1059  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects Bonjour-based mDNS enumeration or use of system tools (e.g., dns-sd, nmap) to find active services via multicast probing or targeted scans.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1059](https://attack.mitre.org/detectionstrategies/DET0376#AN1059)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
