---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1382"
source_url: "https://attack.mitre.org/detectionstrategies/DET0501#AN1382"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1382: Analytic 1382

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1382  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects GCC or Clang invoked on suspicious file paths (e.g., /tmp/, ~/Downloads) with output to executable binaries, followed by execution or outbound traffic from these binaries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1382](https://attack.mitre.org/detectionstrategies/DET0501#AN1382)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
