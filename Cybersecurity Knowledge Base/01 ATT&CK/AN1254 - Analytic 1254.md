---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1254"
source_url: "https://attack.mitre.org/detectionstrategies/DET0457#AN1254"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1254: Analytic 1254

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1254  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Anomalous use of ICMP or UDP by non-network service processes for data exfiltration or remote control, especially if traffic bypasses proxy infrastructure or shows unusual flow patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1254](https://attack.mitre.org/detectionstrategies/DET0457#AN1254)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
