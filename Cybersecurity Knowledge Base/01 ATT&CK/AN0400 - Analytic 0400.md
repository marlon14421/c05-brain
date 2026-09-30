---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0400"
source_url: "https://attack.mitre.org/detectionstrategies/DET0143#AN0400"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0400: Analytic 0400

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0400  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Processes that typically do not perform cryptographic operations loading symmetric encryption libraries (e.g., bcryptprimitives.dll, aes.dll), then initiating outbound connections with high-entropy payloads. Defender correlates process creation, DLL load, and anomalous encrypted traffic patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0400](https://attack.mitre.org/detectionstrategies/DET0143#AN0400)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
