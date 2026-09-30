---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0374"
source_url: "https://attack.mitre.org/detectionstrategies/DET0132#AN0374"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0374: Analytic 0374

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0374  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

User-mode application uses flock() or NSDistributedLock to gain exclusive access to a resource file (e.g., /tmp/guard.lock), conditional logic alters execution if already locked.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0374](https://attack.mitre.org/detectionstrategies/DET0132#AN0374)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
