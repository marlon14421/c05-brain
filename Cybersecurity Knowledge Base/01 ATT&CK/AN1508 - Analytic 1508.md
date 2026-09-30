---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1508"
source_url: "https://attack.mitre.org/detectionstrategies/DET0547#AN1508"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1508: Analytic 1508

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1508  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Abuse of extensible server modules (e.g., Apache, Nginx, Tomcat) to load rogue plugins that initiate bash, connect to C2, or spawn reverse shells.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1508](https://attack.mitre.org/detectionstrategies/DET0547#AN1508)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
