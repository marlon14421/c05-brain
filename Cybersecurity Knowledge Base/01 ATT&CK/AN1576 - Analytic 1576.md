---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1576"
source_url: "https://attack.mitre.org/detectionstrategies/DET0571#AN1576"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1576: Analytic 1576

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1576  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects creation or modification of `systemd` service units, addition of cron jobs that invoke binaries on boot, or suspicious writes to `/etc/init.d/`. Monitors `chmod +x` and `systemctl` execution paths, especially from non-root parent processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1576](https://attack.mitre.org/detectionstrategies/DET0571#AN1576)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
