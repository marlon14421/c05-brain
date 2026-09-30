---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1485"
source_url: "https://attack.mitre.org/detectionstrategies/DET0538#AN1485"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1485: Analytic 1485

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1485  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

launchd or user-invoked processes (ssh, socat) encapsulating traffic via SSH tunnels, VPN-style tooling, or DNS-over-HTTPS clients. Defender sees outbound TLS traffic with embedded DNS or RDP payloads.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1485](https://attack.mitre.org/detectionstrategies/DET0538#AN1485)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
