---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0767"
source_url: "https://attack.mitre.org/detectionstrategies/DET0275#AN0767"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0767: Analytic 0767

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0767  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

An adversary leverages built-in tools such as certutil.exe, powershell.exe, or copy.exe to decode, reassemble, or extract hidden malicious content from obfuscated containers or encoded formats. The decoding utility often spawns shortly after file staging or download and may be chained with script interpreters or further payload execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0767](https://attack.mitre.org/detectionstrategies/DET0275#AN0767)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
