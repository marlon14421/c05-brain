---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1464"
source_url: "https://attack.mitre.org/detectionstrategies/DET0528#AN1464"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1464: Analytic 1464

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1464  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of PubPrn.vbs via cscript.exe using the 'script:' moniker to load and execute a remote .sct scriptlet file, bypassing signature validation and proxying remote payloads through a signed Microsoft script host.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1464](https://attack.mitre.org/detectionstrategies/DET0528#AN1464)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
