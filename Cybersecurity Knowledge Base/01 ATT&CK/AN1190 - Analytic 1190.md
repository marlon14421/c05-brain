---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1190"
source_url: "https://attack.mitre.org/detectionstrategies/DET0425#AN1190"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1190: Analytic 1190

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1190  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects command-line tools, agents, or scripts making outbound HTTPS connections to popular web services like Discord, Slack, Dropbox, or Graph API in an unusual context.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1190](https://attack.mitre.org/detectionstrategies/DET0425#AN1190)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
