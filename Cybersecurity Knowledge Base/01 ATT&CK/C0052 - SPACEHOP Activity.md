---
type: "Campaign"
source: MITRE ATT&CK
id: "C0052"
source_url: "https://attack.mitre.org/campaigns/C0052"
created: "2025-03-25"
modified: "2026-07-31"
---
# C0052: SPACEHOP Activity

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0052  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[SPACEHOP Activity](https://attack.mitre.org/campaigns/C0052) is conducted through commercially leased Virtual Private Servers (VPS), otherwise known as provisioned Operational Relay Box (ORB) networks. The network leveraged for SPACEHOP Activity enabled China-nexus cyber threat actors – such as [APT5](https://attack.mitre.org/groups/G1023) and [Ke3chang](https://attack.mitre.org/groups/G0004) – to perform network reconnaissance scanning and vulnerability exploitation. SPACEHOP Activity has historically targeted entities in North America, Europe, and the Middle East.(Citation: ORB Mandiant)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0052](https://attack.mitre.org/campaigns/C0052)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
