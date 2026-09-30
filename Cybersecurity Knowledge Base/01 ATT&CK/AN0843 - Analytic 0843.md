---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0843"
source_url: "https://attack.mitre.org/detectionstrategies/DET0302#AN0843"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0843: Analytic 0843

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0843  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

A source performs a short closed-port sequence; the host then modifies iptables/nftables/ufw rules or starts a daemon binding a new socket, followed by a successful connection from the same source.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0843](https://attack.mitre.org/detectionstrategies/DET0302#AN0843)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
