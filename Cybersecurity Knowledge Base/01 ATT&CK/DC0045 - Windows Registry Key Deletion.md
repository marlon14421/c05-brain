---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0045"
source_url: "https://attack.mitre.org/datacomponents/DC0045"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0045: Windows Registry Key Deletion

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0045  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The removal of a registry key within the Windows operating system. *Data Collection Measures:* - Windows Event Logs - Event ID 4658 - Registry Key Handle Closed: Captures when a handle to a registry key is closed, which may indicate deletion. - Event ID 4660 - Object Deleted: Logs when a registry key is deleted. - Sysmon (System Monitor) for Windows - Sysmon Event ID 12 - Registry Key Deleted: Logs when a registry key is removed. - Sysmon Event ID 13 - Registry Value Deleted: Captures removal of specific registry values. - Endpoint Detection and Response (EDR) Solutions - Monitor registry deletions for suspicious behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0045](https://attack.mitre.org/datacomponents/DC0045)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
