---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0325"
source_url: "https://attack.mitre.org/detectionstrategies/DET0117#AN0325"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0325: Analytic 0325

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0325  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Creation or modification of `systemd` service units or cron jobs using deceptive naming and untrusted command paths, often followed by lateral network activity or privilege escalation.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0325](https://attack.mitre.org/detectionstrategies/DET0117#AN0325)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
