---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0938"
source_url: "https://attack.mitre.org/detectionstrategies/DET0330#AN0938"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0938: Analytic 0938

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0938  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Correlation of package install event with execution of postinstall scripts containing unknown binaries or abnormal CLI usage. Look for `/usr/sbin/installer` execution followed by child processes originating from postinstall script.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0938](https://attack.mitre.org/detectionstrategies/DET0330#AN0938)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
