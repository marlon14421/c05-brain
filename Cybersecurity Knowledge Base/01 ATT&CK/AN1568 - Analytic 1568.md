---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1568"
source_url: "https://attack.mitre.org/detectionstrategies/DET0568#AN1568"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1568: Analytic 1568

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1568  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects USB HID device enumeration under `/sys/bus/usb/devices/` and rapid keystroke injection resulting in command execution such as bash or Python scripts launched without interactive user activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1568](https://attack.mitre.org/detectionstrategies/DET0568#AN1568)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
