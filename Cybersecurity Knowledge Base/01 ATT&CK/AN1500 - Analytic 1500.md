---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1500"
source_url: "https://attack.mitre.org/detectionstrategies/DET0543#AN1500"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1500: Analytic 1500

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1500  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Encrypted sessions detected with asymmetric key exchange anomalies on non-standard ports or with invalid/malformed certs. Defender correlates NetFlow/IPFIX with IDS/IPS detecting RSA exchanges outside expected TLS flows.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1500](https://attack.mitre.org/detectionstrategies/DET0543#AN1500)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
