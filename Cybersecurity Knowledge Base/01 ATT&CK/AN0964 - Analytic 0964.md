---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0964"
source_url: "https://attack.mitre.org/detectionstrategies/DET0340#AN0964"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0964: Analytic 0964

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0964  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

User pastes an obfuscated command into Terminal.app/iTerm2 that decodes or downloads code and executes. Detects Terminal/iTerm2 spawning bash/zsh/python with suspicious pipeline/base64 patterns followed by file writes in ~/Library or /tmp and outbound network connections.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0964](https://attack.mitre.org/detectionstrategies/DET0340#AN0964)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
