---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1564"
source_url: "https://attack.mitre.org/detectionstrategies/DET0566#AN1564"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1564: Analytic 1564

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1564  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of Office or document viewer processes (e.g., winword.exe) initiating network connections to remote templates or executing scripts due to manipulated template references (e.g., embedded in .docx, .rtf, or .dotm files), followed by suspicious child process creation (e.g., PowerShell).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1564](https://attack.mitre.org/detectionstrategies/DET0566#AN1564)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
