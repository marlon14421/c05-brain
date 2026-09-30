---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1319"
source_url: "https://attack.mitre.org/detectionstrategies/DET0479#AN1319"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1319: Analytic 1319

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1319  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Modification of COR_PROFILER-related environment variables or Registry keys (COR_ENABLE_PROFILING, COR_PROFILER, COR_PROFILER_PATH), combined with anomalous .NET process creation or unmanaged DLL loads. Defender observes registry modifications, suspicious process creation with altered environment variables, and profiler DLLs loaded unexpectedly into .NET CLR processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1319](https://attack.mitre.org/detectionstrategies/DET0479#AN1319)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
