---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0435"
source_url: "https://attack.mitre.org/detectionstrategies/DET0152#AN0435"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0435: Analytic 0435

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0435  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detection focuses on adversaries placing or modifying malicious dylibs in locations searched by legitimate applications. From the defender’s perspective, observable patterns include unexpected creation or modification of dylib files in application bundle paths, unusual module loads by processes compared to historical baselines, and execution of applications loading dylibs from suspicious directories (e.g., /tmp, user-controlled paths). Correlation across file system changes, process execution, and module loads provides high-fidelity detection.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0435](https://attack.mitre.org/detectionstrategies/DET0152#AN0435)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
