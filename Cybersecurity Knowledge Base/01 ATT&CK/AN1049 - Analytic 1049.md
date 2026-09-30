---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1049"
source_url: "https://attack.mitre.org/detectionstrategies/DET0372#AN1049"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1049: Analytic 1049

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1049  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Shell scripts or binaries invoking repeated 'sleep', 'ping', or low-level syscalls (e.g., nanosleep) in short-lived execution chains with no user or system interaction. Frequently seen in malicious cron jobs or payload stagers.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1049](https://attack.mitre.org/detectionstrategies/DET0372#AN1049)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
