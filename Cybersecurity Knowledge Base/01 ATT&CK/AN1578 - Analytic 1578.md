---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1578"
source_url: "https://attack.mitre.org/detectionstrategies/DET0571#AN1578"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1578: Analytic 1578

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1578  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Detects creation of new container system processes via `docker run --restart`, `kubectl exec` to init containers, or modification of container init specs. Flags container images that override entrypoints to embed persistence behaviors.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1578](https://attack.mitre.org/detectionstrategies/DET0571#AN1578)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
