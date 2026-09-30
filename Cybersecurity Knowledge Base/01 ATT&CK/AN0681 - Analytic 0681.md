---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0681"
source_url: "https://attack.mitre.org/detectionstrategies/DET0243#AN0681"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0681: Analytic 0681

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0681  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Defenders may observe attempts to alter cryptographic settings on network devices that reduce key strength or allowable cipher suites. Suspicious indicators include configuration changes that downgrade encryption algorithms, key length parameters, or the disabling of strong encryption in favor of legacy ciphers. These activities often appear as CLI commands modifying crypto policies, firmware changes affecting crypto libraries, or unexpected updates to key management files. Correlation across device config logs and traffic analysis showing weaker ciphers provides higher confidence of malicious key space reduction.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0681](https://attack.mitre.org/detectionstrategies/DET0243#AN0681)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
