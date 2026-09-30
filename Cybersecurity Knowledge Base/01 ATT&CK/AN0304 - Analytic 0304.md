---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0304"
source_url: "https://attack.mitre.org/detectionstrategies/DET0108#AN0304"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0304: Analytic 0304

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0304  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Processes use built-in encoding utilities (e.g., `base64`, `xxd`, or `plutil`) to encode file contents followed by HTTP/HTTPS transfer via curl or custom applications.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0304](https://attack.mitre.org/detectionstrategies/DET0108#AN0304)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
