---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1636"
source_url: "https://attack.mitre.org/detectionstrategies/DET0595#AN1636"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1636: Analytic 1636

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1636  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detects exploitation of IaaS cloud security boundaries to evade defense controls. Defender perspective includes anomalous API calls that bypass audit logging, disable monitoring, or manipulate guardrails (e.g., CloudTrail tampering). Correlation highlights when exploitation attempts precede sudden absence of expected telemetry.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1636](https://attack.mitre.org/detectionstrategies/DET0595#AN1636)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
