---
type: "Campaign"
source: MITRE ATT&CK
id: "C0055"
source_url: "https://attack.mitre.org/campaigns/C0055"
created: "2025-06-04"
modified: "2026-07-31"
---
# C0055: Quad7 Activity

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0055  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Quad7 Activity, also known as CovertNetwork-1658 or the 7777 Botnet, is a network of compromised small office/home office (SOHO) routers. (Citation: Bitsight 7777 Botnet) (Citation: Microsoft Storm-0940) The botnet was initially composed primarily of TP-Link routers and was named Quad7 due to compromised devices exposing TCP port 7777 with the distinctive banner xlogin . Later activity showed a significant increase in compromised Asus routers and the addition of new ports and banners, including TCP port 63256 displaying alogin . Quad7 infrastructure functions as a collection of egress IPs that various China-affiliated threat actors have used to conduct password-spraying and brute-force operations. (Citation: Bitsight 7777 Botnet)(Citation: Medium 777-Botnet) Microsoft has reported that Storm-0940 leveraged credentials obtained through Quad7 Activity to target organizations in North America and Europe, including government agencies, non-governmental organizations, think tanks, law firms, energy firms, IT providers, and defense industrial base entities. (Citation: Microsoft Storm-0940)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0055](https://attack.mitre.org/campaigns/C0055)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
