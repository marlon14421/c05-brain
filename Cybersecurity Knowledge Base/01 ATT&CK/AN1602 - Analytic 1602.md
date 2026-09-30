---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1602"
source_url: "https://attack.mitre.org/detectionstrategies/DET0581#AN1602"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1602: Analytic 1602

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1602  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

ESXi shell or scheduled tasks initiating outbound HTTPS to known public services without inbound return or loggable response, used to fetch instructions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1602](https://attack.mitre.org/detectionstrategies/DET0581#AN1602)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
