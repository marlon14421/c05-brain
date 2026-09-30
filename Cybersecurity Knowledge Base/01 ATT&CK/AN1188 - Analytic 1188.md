---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1188"
source_url: "https://attack.mitre.org/detectionstrategies/DET0424#AN1188"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1188: Analytic 1188

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1188  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Creation, deletion, or modification of security groups and firewall rules in cloud control plane logs that expand access to cloud resources beyond expected baselines. Defender view: unexpected ingress/egress rules permitting 0.0.0.0/0 or opening atypical ports, often correlated with privileged role or API key activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1188](https://attack.mitre.org/detectionstrategies/DET0424#AN1188)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
