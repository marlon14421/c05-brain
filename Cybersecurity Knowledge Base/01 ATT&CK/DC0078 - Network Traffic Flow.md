---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0078"
source_url: "https://attack.mitre.org/datacomponents/DC0078"
created: "2021-10-20"
modified: "2026-05-12"
---
# DC0078: Network Traffic Flow

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0078  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Summarized network packet data that captures session-level details such as source/destination IPs, ports, protocol types, timestamps, and data volume, without storing full packet payloads. This is commonly used for traffic analysis, anomaly detection, and network performance monitoring.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0078](https://attack.mitre.org/datacomponents/DC0078)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
