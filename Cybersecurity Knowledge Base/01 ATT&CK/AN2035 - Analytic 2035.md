---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2035"
source_url: "https://attack.mitre.org/detectionstrategies/DET0899#AN2035"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2035: Analytic 2035

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2035  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects user execution of newly received content or instructions shortly after external communication, including script launches, Office child process spawning, browser-to-script execution chains, or credential prompts followed by new logon sessions.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2035](https://attack.mitre.org/detectionstrategies/DET0899#AN2035)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
