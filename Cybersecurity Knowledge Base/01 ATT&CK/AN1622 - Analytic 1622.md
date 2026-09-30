---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1622"
source_url: "https://attack.mitre.org/detectionstrategies/DET0590#AN1622"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1622: Analytic 1622

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1622  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary modifies externally-facing web content by accessing and overwriting hosted HTML/JS/CSS files, typically following web shell deployment, credential abuse, or exploitation of web application vulnerabilities.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1622](https://attack.mitre.org/detectionstrategies/DET0590#AN1622)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
