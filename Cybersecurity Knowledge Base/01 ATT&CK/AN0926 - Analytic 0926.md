---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0926"
source_url: "https://attack.mitre.org/detectionstrategies/DET0325#AN0926"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0926: Analytic 0926

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0926  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Changes to NAT/firewall policies enabling outbound port forwarding from internal IPs to Internet-based proxy endpoints. Log spikes in outbound flows to CDN, VPS, or anomalous ASNs with few return packets.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0926](https://attack.mitre.org/detectionstrategies/DET0325#AN0926)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
