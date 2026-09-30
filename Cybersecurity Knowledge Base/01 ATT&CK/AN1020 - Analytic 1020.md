---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1020"
source_url: "https://attack.mitre.org/detectionstrategies/DET0359#AN1020"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1020: Analytic 1020

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1020  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Suspicious processes (e.g., Tor clients, relays, unknown binaries) launch with sustained encrypted outbound traffic to known anonymity infrastructure (e.g., Tor, I2P), and may relay to additional internal systems via reverse proxying, ICMP tunneling, or socket forwarding.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1020](https://attack.mitre.org/detectionstrategies/DET0359#AN1020)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
