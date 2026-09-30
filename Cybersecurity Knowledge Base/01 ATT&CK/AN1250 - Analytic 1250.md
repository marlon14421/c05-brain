---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1250"
source_url: "https://attack.mitre.org/detectionstrategies/DET0454#AN1250"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1250: Analytic 1250

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1250  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects unauthorized modifications to PAM configuration files or shared object modules. Correlates file modification events under /etc/pam.d/ or /lib/security/ with unusual authentication activity such as multiple simultaneous logins, off-hours logins, or logons without corresponding physical/VPN access.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1250](https://attack.mitre.org/detectionstrategies/DET0454#AN1250)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
