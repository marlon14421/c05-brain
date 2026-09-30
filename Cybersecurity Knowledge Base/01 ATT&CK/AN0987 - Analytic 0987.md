---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0987"
source_url: "https://attack.mitre.org/detectionstrategies/DET0347#AN0987"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0987: Analytic 0987

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0987  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detects VIBs, scripts, or binaries placed into directories like /bin or /etc/vmware with names mimicking standard ESXi components. Also monitors unauthorized creation of services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0987](https://attack.mitre.org/detectionstrategies/DET0347#AN0987)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
