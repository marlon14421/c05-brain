---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0222"
source_url: "https://attack.mitre.org/detectionstrategies/DET0080#AN0222"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0222: Analytic 0222

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0222  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Adversary exploits containerized app via ingress or service. Chain: (1) suspicious request in ingress/app logs → (2) container process spawns a shell/exec/sidecar (kubectl exec/docker exec) → (3) egress to Internet or metadata service (169.254.169.254).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0222](https://attack.mitre.org/detectionstrategies/DET0080#AN0222)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
