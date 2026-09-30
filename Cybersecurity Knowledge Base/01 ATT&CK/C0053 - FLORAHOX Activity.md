---
type: "Campaign"
source: MITRE ATT&CK
id: "C0053"
source_url: "https://attack.mitre.org/campaigns/C0053"
created: "2025-03-25"
modified: "2026-07-31"
---
# C0053: FLORAHOX Activity

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0053  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[FLORAHOX Activity](https://attack.mitre.org/campaigns/C0053) is conducted using a hybrid operational relay box (ORB) network, which combines two types of infrastructure: compromised devices and leased Virtual Private Servers (VPS). The compromised devices include end-of-life routers and IoT devices, while VPS space is commercially leased and managed by ORB network administrators. This hybrid ORB network allows adversaries to proxy and obscure malicious traffic, making the source of the traffic more difficult to trace. The FLORAHOX ORB network has been leveraged by multiple cyber threat actors, including China-nexus actors like [ZIRCONIUM](https://attack.mitre.org/groups/G0128). These adversaries conduct espionage campaigns through [FLORAHOX Activity](https://attack.mitre.org/campaigns/C0053), relying on the ORB network's ability to funnel traffic through [Tor](https://attack.mitre.org/software/S0183) nodes, provisioned VPS servers, and compromised routers to obfuscate malicious traffic.(Citation: ORB Mandiant)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0053](https://attack.mitre.org/campaigns/C0053)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
