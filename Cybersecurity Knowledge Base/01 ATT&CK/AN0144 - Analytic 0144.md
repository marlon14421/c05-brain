---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0144"
source_url: "https://attack.mitre.org/detectionstrategies/DET0053#AN0144"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0144: Analytic 0144

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0144  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects excessive outbound traffic to remote host over HTTP(S) from uncommon or previously unseen processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0144](https://attack.mitre.org/detectionstrategies/DET0053#AN0144)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
