---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1423"
source_url: "https://attack.mitre.org/detectionstrategies/DET0515#AN1423"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1423: Analytic 1423

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1423  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Access and retrieval of container service account tokens followed by unauthorized API requests using those tokens to interact with the Kubernetes API server or internal services.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1423](https://attack.mitre.org/detectionstrategies/DET0515#AN1423)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
