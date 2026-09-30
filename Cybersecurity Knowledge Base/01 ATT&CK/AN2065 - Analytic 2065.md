---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2065"
source_url: "https://attack.mitre.org/detectionstrategies/DET0920#AN2065"
created: "2026-04-23"
modified: "2026-04-24"
---
# AN2065: Analytic 2065

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2065  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection identifies execution of scripts or applications containing invisible Unicode payloads reconstructed at runtime, correlated with abnormal AppleScript, JavaScript for Automation, or shell execution and subsequent process or network behavior inconsistent with visible file content.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2065](https://attack.mitre.org/detectionstrategies/DET0920#AN2065)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
