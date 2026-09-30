---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0050"
source_url: "https://attack.mitre.org/datacomponents/DC0050"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0050: Windows Registry Key Access

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0050  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The action of opening a specific Windows Registry key, typically to read its associated value. This activity can be used for system configuration, application settings retrieval, and security policies.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0050](https://attack.mitre.org/datacomponents/DC0050)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
