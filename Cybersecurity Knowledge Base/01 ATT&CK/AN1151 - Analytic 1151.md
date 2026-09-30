---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1151"
source_url: "https://attack.mitre.org/detectionstrategies/DET0411#AN1151"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1151: Analytic 1151

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1151  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Inspect network telemetry for adversary attempts to blend malicious traffic with legitimate flows using VPNs, proxies, or geolocation spoofing. Defensive teams may observe anomalous tunnels, encrypted sessions to suspicious domains, or geo-mismatched IP activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1151](https://attack.mitre.org/detectionstrategies/DET0411#AN1151)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
