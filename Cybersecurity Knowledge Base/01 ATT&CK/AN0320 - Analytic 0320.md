---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0320"
source_url: "https://attack.mitre.org/detectionstrategies/DET0115#AN0320"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0320: Analytic 0320

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0320  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Inbound spearphishing attempts delivered via third-party services (e.g., Gmail, LinkedIn messages) leading to malicious file downloads or browser-initiated script execution. Defender view includes correlation of external service logins, unexpected file write operations, and suspicious descendant processes spawned from productivity or browser applications.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0320](https://attack.mitre.org/detectionstrategies/DET0115#AN0320)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
