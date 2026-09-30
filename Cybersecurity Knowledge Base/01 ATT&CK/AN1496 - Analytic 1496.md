---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1496"
source_url: "https://attack.mitre.org/detectionstrategies/DET0543#AN1496"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1496: Analytic 1496

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1496  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes not typically associated with encryption loading asymmetric crypto libraries (e.g., rsaenh.dll, crypt32.dll) and subsequently initiating outbound TLS/SSL connections with abnormal certificate chains or handshakes. Defender correlates process creation, module load, and unusual encrypted sessions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1496](https://attack.mitre.org/detectionstrategies/DET0543#AN1496)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
