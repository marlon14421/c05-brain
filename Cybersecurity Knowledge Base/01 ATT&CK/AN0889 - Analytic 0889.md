---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0889"
source_url: "https://attack.mitre.org/detectionstrategies/DET0317#AN0889"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0889: Analytic 0889

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0889  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Modification of container runtime security profiles (AppArmor, seccomp) or removal of monitoring agents within containers. Detect unauthorized mounting/unmounting of host /proc or /sys to disable logging or auditing.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0889](https://attack.mitre.org/detectionstrategies/DET0317#AN0889)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
