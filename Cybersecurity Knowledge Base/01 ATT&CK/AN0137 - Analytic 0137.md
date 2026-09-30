---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0137"
source_url: "https://attack.mitre.org/detectionstrategies/DET0050#AN0137"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0137: Analytic 0137

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0137  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

An adversary writes or drops a malicious Office Add-in (e.g., WLL, XLL, COM) to a trusted directory or modifies registry keys to load malicious add-ins on Office application launch. Upon user opening Word or Excel, the add-in is automatically loaded, triggering execution of the payload, often spawning scripting engines or anomalous child processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0137](https://attack.mitre.org/detectionstrategies/DET0050#AN0137)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
