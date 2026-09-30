---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0250"
source_url: "https://attack.mitre.org/detectionstrategies/DET0091#AN0250"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0250: Analytic 0250

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0250  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Behavioral chain involving suspicious use of GetProcAddress and LoadLibrary following memory allocation and manual mapping, often paired with low entropy strings, abnormal API use without static import tables, or delayed module load behaviors.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0250](https://attack.mitre.org/detectionstrategies/DET0091#AN0250)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
