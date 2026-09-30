---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0628"
source_url: "https://attack.mitre.org/detectionstrategies/DET0224#AN0628"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0628: Analytic 0628

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0628  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detects anomalous use of COM objects for execution, such as Office applications spawning scripting engines, enumeration of COM interfaces via registry queries, or processes loading atypical DLLs through COM activation. Correlates process creation, module loads, and registry queries to flag suspicious COM-based code execution or persistence.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0628](https://attack.mitre.org/detectionstrategies/DET0224#AN0628)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
