---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0181"
source_url: "https://attack.mitre.org/detectionstrategies/DET0067#AN0181"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0181: Analytic 0181

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0181  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Execution of processes using nohup or shell redirection to ignore SIGHUP and continue running after session termination. Defender perspective: correlation between commands including nohup, disowned jobs, or `&` suffix with continued process execution after parent terminal exit.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0181](https://attack.mitre.org/detectionstrategies/DET0067#AN0181)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
