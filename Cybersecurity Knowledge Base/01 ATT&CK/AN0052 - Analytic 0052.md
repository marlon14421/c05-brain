---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0052"
source_url: "https://attack.mitre.org/detectionstrategies/DET0018#AN0052"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0052: Analytic 0052

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0052  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

A process (often LOLBin or user-launched program) loads a DLL from a user-writable/UNC/Temp path or unsigned/invalid signer. Within a short window the DLL is (a) newly written to disk, (b) spawned as follow-on execution (rundll32/regsvr32), or (c) establishes outbound C2.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0052](https://attack.mitre.org/detectionstrategies/DET0018#AN0052)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
