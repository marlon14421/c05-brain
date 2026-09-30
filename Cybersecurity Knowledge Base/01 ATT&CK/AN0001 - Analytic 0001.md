---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0001"
source_url: "https://attack.mitre.org/detectionstrategies/DET0001#AN0001"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0001: Analytic 0001

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0001  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects access attempts to cloud instance metadata endpoints (e.g., 169.254.169.254) from virtual machines or containerized workloads. This includes both direct access and SSRF exploitation patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0001](https://attack.mitre.org/detectionstrategies/DET0001#AN0001)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
