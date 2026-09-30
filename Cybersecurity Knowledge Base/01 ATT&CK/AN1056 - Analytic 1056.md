---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1056"
source_url: "https://attack.mitre.org/detectionstrategies/DET0375#AN1056"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1056: Analytic 1056

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1056  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Monitor for creation or modification of udev rules files in key directories (/etc/udev/rules.d/, /lib/udev/rules.d/, /usr/lib/udev/rules.d/). Look for RUN+= or IMPORT keys invoking suspicious binaries or scripts. Correlate this with process execution from systemd-udevd context, and file writes near udev reload/restart events. Combine this with unexpected background process spawning from udevd-related forks.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1056](https://attack.mitre.org/detectionstrategies/DET0375#AN1056)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
