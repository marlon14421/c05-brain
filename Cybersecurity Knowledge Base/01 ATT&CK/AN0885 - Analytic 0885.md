---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0885"
source_url: "https://attack.mitre.org/detectionstrategies/DET0316#AN0885"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0885: Analytic 0885

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0885  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Execution of CLI commands erasing file systems or storage (erase flash:, format disk, erase nvram:). Detect authentication events followed by destructive commands within the same privileged session.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0885](https://attack.mitre.org/detectionstrategies/DET0316#AN0885)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
