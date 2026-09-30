---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0403"
source_url: "https://attack.mitre.org/detectionstrategies/DET0143#AN0403"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0403: Analytic 0403

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0403  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

ESXi daemons (hostd, vpxa) unexpectedly using symmetric encryption routines for external connections. Defender identifies logs of service traffic with encrypted payloads inconsistent with VMware management baselines.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0403](https://attack.mitre.org/detectionstrategies/DET0143#AN0403)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
