---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1258"
source_url: "https://attack.mitre.org/detectionstrategies/DET0457#AN1258"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1258: Analytic 1258

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1258  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Non-standard port/protocol pairings or low-entropy ICMP traffic resembling tunneling patterns (e.g., fixed-size pings with delays).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1258](https://attack.mitre.org/detectionstrategies/DET0457#AN1258)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
