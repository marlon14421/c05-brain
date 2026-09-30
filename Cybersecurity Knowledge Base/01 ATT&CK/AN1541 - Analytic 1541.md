---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1541"
source_url: "https://attack.mitre.org/detectionstrategies/DET0559#AN1541"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1541: Analytic 1541

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1541  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detect commands such as 'esxcli system shutdown' or 'vim-cmd vmsvc/power.shutdown' executed outside of maintenance windows or via unusual users. Reboot logs in hostd.log and shell logs should be correlated.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1541](https://attack.mitre.org/detectionstrategies/DET0559#AN1541)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
