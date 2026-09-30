---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0898"
source_url: "https://attack.mitre.org/detectionstrategies/DET0318#AN0898"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0898: Analytic 0898

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0898  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

ESXi host processes (vmx, hostd) initiating HTTPS sessions toward external code repositories. Defender perspective: detect datastore reads followed by outbound web traffic inconsistent with administrative baselines.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0898](https://attack.mitre.org/detectionstrategies/DET0318#AN0898)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
