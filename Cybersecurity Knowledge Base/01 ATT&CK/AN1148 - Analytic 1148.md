---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1148"
source_url: "https://attack.mitre.org/detectionstrategies/DET0411#AN1148"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1148: Analytic 1148

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1148  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor DNS queries, proxy logs, and user-agent strings for anomalous patterns associated with adversary attempts to hide infrastructure. Defenders may observe DNS resolutions to short-lived domains, abnormal WHOIS registration data, or filtering of known defensive/responder IP addresses.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1148](https://attack.mitre.org/detectionstrategies/DET0411#AN1148)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
