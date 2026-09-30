---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0934"
source_url: "https://attack.mitre.org/detectionstrategies/DET0329#AN0934"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0934: Analytic 0934

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0934  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Shell utilities or scripts deleting `/etc/systemd/system/rescue.target`, `/etc/fstab` backups, or `/boot/efi` partitions; chattr used to block snapshot auto-recovery

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0934](https://attack.mitre.org/detectionstrategies/DET0329#AN0934)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
