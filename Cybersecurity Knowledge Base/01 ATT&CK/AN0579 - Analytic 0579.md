---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0579"
source_url: "https://attack.mitre.org/detectionstrategies/DET0203#AN0579"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0579: Analytic 0579

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0579  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects ptrace-based process injection by correlating audit logs of ptrace syscalls, memory modifications (e.g., poketext, pokedata), and suspicious register manipulation on a target process not normally debugged by the originator. Alerts on processes attempting to ptrace non-child or privileged processes, especially those followed by abnormal memory or execution behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0579](https://attack.mitre.org/detectionstrategies/DET0203#AN0579)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
