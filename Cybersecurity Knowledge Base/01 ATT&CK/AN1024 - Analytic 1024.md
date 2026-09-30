---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1024"
source_url: "https://attack.mitre.org/detectionstrategies/DET0359#AN1024"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1024: Analytic 1024

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1024  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Encrypted traffic or ICMP tunneling from border routers to internal routers or unknown external IPs. Forwarded traffic shows consistent hop-to-hop relaying without matching configured VPN or expected network topology.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1024](https://attack.mitre.org/detectionstrategies/DET0359#AN1024)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
