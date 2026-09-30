---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1045"
source_url: "https://attack.mitre.org/detectionstrategies/DET0371#AN1045"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1045: Analytic 1045

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1045  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Monitor for suspicious use of Windows API calls such as IsDebuggerPresent() and NtQueryInformationProcess(), or processes manually checking the BeingDebugged flag in the Process Environment Block (PEB). Detect sequences of OutputDebugStringW() calls in short intervals that may indicate debugger flooding attempts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1045](https://attack.mitre.org/detectionstrategies/DET0371#AN1045)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
