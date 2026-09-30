---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0807"
source_url: "https://attack.mitre.org/detectionstrategies/DET0290#AN0807"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0807: Analytic 0807

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0807  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects direct modification of crontab entries in /var/spool/cron/crontabs/root or /etc/rc.local.d/local.sh followed by execution of scripts linked to lateral movement or malware persistence.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0807](https://attack.mitre.org/detectionstrategies/DET0290#AN0807)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
