---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2036"
source_url: "https://attack.mitre.org/detectionstrategies/DET0899#AN2036"
created: "2026-04-16"
modified: "2026-05-12"
---
# AN2036: Analytic 2036

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2036  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects user-authorized execution of downloaded content or scripts after communication prompts, including browser downloads followed by osascript, shell, or installer execution and subsequent network activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2036](https://attack.mitre.org/detectionstrategies/DET0899#AN2036)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
