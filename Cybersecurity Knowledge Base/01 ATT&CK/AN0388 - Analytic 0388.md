---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0388"
source_url: "https://attack.mitre.org/detectionstrategies/DET0138#AN0388"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0388: Analytic 0388

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0388  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of InstallUtil.exe from .NET framework directories with arguments specifying non-standard or attacker-supplied assemblies, especially when followed by suspicious child process creation or script execution. Detection also includes correlation of newly created binaries prior to InstallUtil invocation and anomalous command-line usage compared to historical baselines.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0388](https://attack.mitre.org/detectionstrategies/DET0138#AN0388)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
