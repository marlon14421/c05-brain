---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1110"
source_url: "https://attack.mitre.org/detectionstrategies/DET0394#AN1110"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1110: Analytic 1110

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1110  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Web servers (e.g., httpd) spawning abnormal processes post file upload into /Library/WebServer/Documents or /usr/local/var/www

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1110](https://attack.mitre.org/detectionstrategies/DET0394#AN1110)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
