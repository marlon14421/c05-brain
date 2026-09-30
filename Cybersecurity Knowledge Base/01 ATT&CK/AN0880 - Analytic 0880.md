---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0880"
source_url: "https://attack.mitre.org/detectionstrategies/DET0315#AN0880"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0880: Analytic 0880

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0880  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversaries create the 'Office Test\Special\Perf' registry key and specify a malicious DLL path that is auto-loaded when an Office application starts. This DLL is injected into the Office process memory space and can provide persistent execution without requiring macro enablement.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0880](https://attack.mitre.org/detectionstrategies/DET0315#AN0880)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
