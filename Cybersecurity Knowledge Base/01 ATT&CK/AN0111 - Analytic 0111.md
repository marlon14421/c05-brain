---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0111"
source_url: "https://attack.mitre.org/detectionstrategies/DET0039#AN0111"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0111: Analytic 0111

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0111  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Inspect unified logs for anomalous DNS resolutions triggered by non-network applications. Flag repeated connections to newly registered or algorithmically generated domains. Correlate with endpoint process telemetry.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0111](https://attack.mitre.org/detectionstrategies/DET0039#AN0111)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
