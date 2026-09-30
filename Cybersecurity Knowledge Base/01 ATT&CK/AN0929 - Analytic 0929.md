---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0929"
source_url: "https://attack.mitre.org/detectionstrategies/DET0326#AN0929"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0929: Analytic 0929

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0929  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

EndpointSecurity/Unified Logs show processes generating custom alphabets or long high-entropy, non-standard tokens → network logs (PF/Zeek/EDR) show asymmetric beacons, protocol mismatches, or periodic fixed-size posts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0929](https://attack.mitre.org/detectionstrategies/DET0326#AN0929)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
