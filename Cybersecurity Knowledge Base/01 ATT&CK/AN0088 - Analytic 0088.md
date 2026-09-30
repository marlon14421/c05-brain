---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0088"
source_url: "https://attack.mitre.org/detectionstrategies/DET0030#AN0088"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0088: Analytic 0088

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0088  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Detects suspicious updates to conditional access or MFA enforcement policies in identity providers such as Entra ID, Okta, or JumpCloud. Focus is on removal of policy blocks, addition of broad exclusions, or registration of adversary-controlled MFA methods, followed by anomalous login activity that takes advantage of the modified policies.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0088](https://attack.mitre.org/detectionstrategies/DET0030#AN0088)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
