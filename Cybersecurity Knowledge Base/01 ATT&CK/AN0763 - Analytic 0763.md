---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0763"
source_url: "https://attack.mitre.org/detectionstrategies/DET0273#AN0763"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0763: Analytic 0763

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0763  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Unusual TLS tunnels through ports not normally encrypted (e.g., TLS on port 8080, 53). Defender sees NetFlow/IPFIX or packet inspection indicating high-entropy traffic volumes and asymmetric client/server exchange ratios.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0763](https://attack.mitre.org/detectionstrategies/DET0273#AN0763)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
