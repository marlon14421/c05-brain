---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0814"
source_url: "https://attack.mitre.org/detectionstrategies/DET0293#AN0814"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0814: Analytic 0814

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0814  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects injection or tampering of DLLs in hybrid identity agents (e.g., AzureADConnectAuthenticationAgentService), registry or configuration changes tied to PTA/AD FS, and anomalous LSASS or AD FS module loads correlated with authentication anomalies.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0814](https://attack.mitre.org/detectionstrategies/DET0293#AN0814)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
