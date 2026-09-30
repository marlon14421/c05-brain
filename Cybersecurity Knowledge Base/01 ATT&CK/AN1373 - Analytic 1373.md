---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1373"
source_url: "https://attack.mitre.org/detectionstrategies/DET0497#AN1373"
created: "2025-10-21"
modified: "2026-05-12"
---
# AN1373: Analytic 1373

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1373  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Detects disabling container runtime security controls, removing sidecar sensors, modifying seccomp/AppArmor profiles, mounting host proc/sys paths to interfere with host logging, or killing in-container monitoring agents.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1373](https://attack.mitre.org/detectionstrategies/DET0497#AN1373)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
