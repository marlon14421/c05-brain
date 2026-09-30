---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0084"
source_url: "https://attack.mitre.org/detectionstrategies/DET0028#AN0084"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0084: Analytic 0084

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0084  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Virtual instances or workloads generating sustained outbound data rates, often to TOR, VPN, or proxy endpoints. Often coincides with unusual IAM usage or deployed scripts (e.g., cron jobs using proxy clients).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0084](https://attack.mitre.org/detectionstrategies/DET0028#AN0084)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
