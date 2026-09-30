---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1345"
source_url: "https://attack.mitre.org/detectionstrategies/DET0488#AN1345"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1345: Analytic 1345

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1345  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Behavioral chain: (1) sshd or federated SSO logins from third-party networks or identities; (2) rapid sudo/su privilege elevation; (3) access to sensitive paths or east-west SSH. Correlate auth logs, process execution, and network flows.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1345](https://attack.mitre.org/detectionstrategies/DET0488#AN1345)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
