---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0932"
source_url: "https://attack.mitre.org/detectionstrategies/DET0328#AN0932"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0932: Analytic 0932

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0932  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Execution of CMSTP.exe with arguments pointing to suspicious or remote INF/SCT/DLL payloads, optionally followed by outbound network connections to untrusted IPs, process injection via COM interfaces (CMSTPLUA, CMLUAUTIL), registry modifications registering malicious profiles, or creation of suspicious INF/DLL/SCT files prior to execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0932](https://attack.mitre.org/detectionstrategies/DET0328#AN0932)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
