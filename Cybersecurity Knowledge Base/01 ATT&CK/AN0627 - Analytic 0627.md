---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0627"
source_url: "https://attack.mitre.org/detectionstrategies/DET0223#AN0627"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0627: Analytic 0627

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0627  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Detects central router or switch config management tools (e.g., FortiManager, Cisco Prime) triggering device reboots or config pushes using abnormal accounts or IPs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0627](https://attack.mitre.org/detectionstrategies/DET0223#AN0627)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
