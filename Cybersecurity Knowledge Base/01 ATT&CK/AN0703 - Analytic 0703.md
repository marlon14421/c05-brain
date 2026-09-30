---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0703"
source_url: "https://attack.mitre.org/detectionstrategies/DET0254#AN0703"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0703: Analytic 0703

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0703  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detect alterations of transmitted data via monitoring syscalls (`send`, `recv`, `write`) or middleware interception. Identify mismatched file hashes when compared at origin vs. destination. Watch for anomalous activity from processes interacting with secure transmission services (e.g., OpenSSL, scp).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0703](https://attack.mitre.org/detectionstrategies/DET0254#AN0703)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
