---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0404"
source_url: "https://attack.mitre.org/detectionstrategies/DET0143#AN0404"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0404: Analytic 0404

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0404  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Flows showing encrypted payloads with high entropy not matching TLS handshake patterns, particularly when occurring on non-standard ports. Defender observes NetFlow/IPFIX byte distribution anomalies or IDS/IPS detecting symmetric encryption patterns without associated key exchange.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0404](https://attack.mitre.org/detectionstrategies/DET0143#AN0404)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
