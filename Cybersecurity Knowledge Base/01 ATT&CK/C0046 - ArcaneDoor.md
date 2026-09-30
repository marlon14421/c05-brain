---
type: "Campaign"
source: MITRE ATT&CK
id: "C0046"
source_url: "https://attack.mitre.org/campaigns/C0046"
created: "2025-01-06"
modified: "2026-07-31"
---
# C0046: ArcaneDoor

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0046  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[ArcaneDoor](https://attack.mitre.org/campaigns/C0046) is a campaign targeting networking devices from Cisco and other vendors between July 2023 and April 2024, primarily focused on government and critical infrastructure networks. [ArcaneDoor](https://attack.mitre.org/campaigns/C0046) is associated with the deployment of the custom backdoors [Line Runner](https://attack.mitre.org/software/S1188) and [Line Dancer](https://attack.mitre.org/software/S1186). [ArcaneDoor](https://attack.mitre.org/campaigns/C0046) is attributed to a group referred to as UAT4356 or STORM-1849, and is assessed to be a state-sponsored campaign.(Citation: Cisco ArcaneDoor 2024)(Citation: CCCS ArcaneDoor 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0046](https://attack.mitre.org/campaigns/C0046)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
