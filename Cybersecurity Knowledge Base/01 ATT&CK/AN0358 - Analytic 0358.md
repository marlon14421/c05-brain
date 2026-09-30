---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0358"
source_url: "https://attack.mitre.org/detectionstrategies/DET0127#AN0358"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0358: Analytic 0358

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0358  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Adversary uses renamed container images, injects files into containers with misleading names or metadata (e.g., renamed system binaries), and executes them during startup or scheduled jobs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0358](https://attack.mitre.org/detectionstrategies/DET0127#AN0358)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
