---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1537"
source_url: "https://attack.mitre.org/detectionstrategies/DET0558#AN1537"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1537: Analytic 1537

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1537  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects suspicious use of ESXi native CLI tools like esxcli and vim-cmd by unauthorized users or outside expected maintenance windows. Focus is on actions such as stopping VMs, reconfiguring network/firewall settings, and enabling SSH or logging.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1537](https://attack.mitre.org/detectionstrategies/DET0558#AN1537)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
