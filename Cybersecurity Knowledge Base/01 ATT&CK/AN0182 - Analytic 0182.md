---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0182"
source_url: "https://attack.mitre.org/detectionstrategies/DET0067#AN0182"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0182: Analytic 0182

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0182  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

PowerShell or script execution with parameters that suppress errors or ignore user interrupts, such as `-ErrorAction SilentlyContinue`. Defender perspective: detecting discrepancies between suppressed error arguments and continued execution behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0182](https://attack.mitre.org/detectionstrategies/DET0067#AN0182)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
