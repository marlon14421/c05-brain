---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0472"
source_url: "https://attack.mitre.org/detectionstrategies/DET0166#AN0472"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0472: Analytic 0472

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0472  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary registers a malicious Microsoft Exchange transport agent DLL (.NET assembly), configures it via PowerShell or Exchange Management Shell, and persists code execution by manipulating email processing logic based on rules or headers.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0472](https://attack.mitre.org/detectionstrategies/DET0166#AN0472)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
