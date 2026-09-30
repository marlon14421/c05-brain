---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0577"
source_url: "https://attack.mitre.org/detectionstrategies/DET0201#AN0577"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0577: Analytic 0577

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0577  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

DLL hijacking behaviors including unexpected DLL loads from non-standard directories, replacement of DLLs, phantom DLL insertion, redirection file creation, and substitution of legitimate DLLs. Defender correlates file system modifications, registry changes, and module load telemetry to detect abnormal DLL behavior in trusted processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0577](https://attack.mitre.org/detectionstrategies/DET0201#AN0577)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
