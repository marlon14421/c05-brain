---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0581"
source_url: "https://attack.mitre.org/detectionstrategies/DET0205#AN0581"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0581: Analytic 0581

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0581  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of XSL scripts via msxsl.exe or wmic.exe using embedded JScript or VBScript for proxy execution. Detection correlates process creation, command-line patterns, and module load behavior of scripting components (e.g., jscript.dll).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0581](https://attack.mitre.org/detectionstrategies/DET0205#AN0581)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
