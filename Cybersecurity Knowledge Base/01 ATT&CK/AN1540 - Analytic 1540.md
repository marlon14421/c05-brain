---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1540"
source_url: "https://attack.mitre.org/detectionstrategies/DET0559#AN1540"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1540: Analytic 1540

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1540  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Identify use of 'shutdown', 'reboot', or 'osascript' system shutdown invocations within unified logs and track unexpected shutdown sequences initiated by GUI or script. Cross-reference with user activity or absence thereof.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1540](https://attack.mitre.org/detectionstrategies/DET0559#AN1540)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
