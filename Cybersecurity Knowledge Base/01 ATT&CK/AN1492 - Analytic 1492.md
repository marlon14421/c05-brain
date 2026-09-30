---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1492"
source_url: "https://attack.mitre.org/detectionstrategies/DET0540#AN1492"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1492: Analytic 1492

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1492  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Ephemeral or unauthorized container instantiation using public images (e.g., from DockerHub) that initiate high CPU usage shortly after startup. Often scheduled via Kubernetes or Docker socket abuse.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1492](https://attack.mitre.org/detectionstrategies/DET0540#AN1492)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
