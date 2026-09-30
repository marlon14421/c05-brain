---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0354"
source_url: "https://attack.mitre.org/detectionstrategies/DET0126#AN0354"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0354: Analytic 0354

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0354  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Use of command-line like `ip ssh pubkey-chain` to bind SSH keys to privileged accounts on routers or switches.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0354](https://attack.mitre.org/detectionstrategies/DET0126#AN0354)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
