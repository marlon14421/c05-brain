---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0775"
source_url: "https://attack.mitre.org/detectionstrategies/DET0278#AN0775"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0775: Analytic 0775

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0775  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detection of writes to /boot or EFI directories outside of expected package manager updates. Monitoring kernel log and auditd events for attempts to overwrite bootloader binaries (e.g., grub, shim). Unexpected execution of efibootmgr or dd writing to /dev/sdX devices followed by boot parameter changes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0775](https://attack.mitre.org/detectionstrategies/DET0278#AN0775)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
