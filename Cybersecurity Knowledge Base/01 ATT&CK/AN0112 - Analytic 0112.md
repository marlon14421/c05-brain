---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0112"
source_url: "https://attack.mitre.org/detectionstrategies/DET0039#AN0112"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0112: Analytic 0112

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0112  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Monitor esxcli and syslog records for DNS resolver changes or repeated queries to unusual external domains by management agents. Detect unauthorized changes to VM or host network settings that redirect DNS lookups.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0112](https://attack.mitre.org/detectionstrategies/DET0039#AN0112)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
