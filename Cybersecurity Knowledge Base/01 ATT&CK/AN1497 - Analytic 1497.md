---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1497"
source_url: "https://attack.mitre.org/detectionstrategies/DET0543#AN1497"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1497: Analytic 1497

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1497  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Processes (e.g., bash, python, custom binaries) dynamically linking libcrypto/libssl for RSA key exchange, then creating external connections with abnormal certificate validation or handshake anomalies. Defender observes syscall traces and outbound asymmetric key exchanges from non-SSL-native processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1497](https://attack.mitre.org/detectionstrategies/DET0543#AN1497)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
