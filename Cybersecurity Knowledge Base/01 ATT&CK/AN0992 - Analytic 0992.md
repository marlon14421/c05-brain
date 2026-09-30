---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0992"
source_url: "https://attack.mitre.org/detectionstrategies/DET0349#AN0992"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0992: Analytic 0992

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0992  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detect suspicious file creations and process executions triggered by browser activity (e.g., injected payloads written to %AppData% or Temp directories, then executed). Correlate network anomalies with subsequent local process creation or script execution.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0992](https://attack.mitre.org/detectionstrategies/DET0349#AN0992)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
