---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1642"
source_url: "https://attack.mitre.org/detectionstrategies/DET0597#AN1642"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1642: Analytic 1642

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1642  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Suspicious access to password manager vaults (KeePassXC, gnome-keyring, pass) via memory scraping or unauthorized file reads. Detects unusual command execution involving gdb/strace attached to password manager processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1642](https://attack.mitre.org/detectionstrategies/DET0597#AN1642)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
