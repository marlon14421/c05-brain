---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1093"
source_url: "https://attack.mitre.org/detectionstrategies/DET0387#AN1093"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1093: Analytic 1093

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1093  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects anomalous ARP cache changes and unsolicited ARP broadcasts using unified logs and packet capture. Behavioral detection includes multiple IP addresses mapped to the same MAC address and repeated gratuitous ARP traffic.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1093](https://attack.mitre.org/detectionstrategies/DET0387#AN1093)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
