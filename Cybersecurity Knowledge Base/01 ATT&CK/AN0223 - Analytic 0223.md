---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0223"
source_url: "https://attack.mitre.org/detectionstrategies/DET0080#AN0223"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0223: Analytic 0223

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0223  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Adversary targets cloud-hosted public endpoints. Chain: (1) ALB/ELB/Cloud LB logs show exploit-like inputs or error spikes → (2) workload spawns shell or reaches metadata API → (3) egress to new external hosts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0223](https://attack.mitre.org/detectionstrategies/DET0080#AN0223)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
