---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0836"
source_url: "https://attack.mitre.org/detectionstrategies/DET0299#AN0836"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0836: Analytic 0836

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0836  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

macOS-specific permission modification behavioral chain: (1) chmod/chown/chflags process execution, (2) System Integrity Protection (SIP) bypass attempts, (3) Extended attribute (xattr) modifications, (4) Unified log correlation with file system events, (5) Subsequent access to previously restricted resources

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0836](https://attack.mitre.org/detectionstrategies/DET0299#AN0836)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
