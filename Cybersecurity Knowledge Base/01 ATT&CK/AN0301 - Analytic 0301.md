---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0301"
source_url: "https://attack.mitre.org/detectionstrategies/DET0107#AN0301"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0301: Analytic 0301

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0301  
**Platforms:** Identity Provider  
**Tactics:** Not specified

## Source description

Detection of OAuth consent phishing or malicious login attempts initiated through spearphishing links. Behavior chain includes inbound email with OAuth URL → consent page visited → unusual token grants logged in IdP logs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0301](https://attack.mitre.org/detectionstrategies/DET0107#AN0301)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
