---
type: "Campaign"
source: MITRE ATT&CK
id: "C0050"
source_url: "https://attack.mitre.org/campaigns/C0050"
created: "2025-02-18"
modified: "2026-07-31"
---
# C0050: J-magic Campaign

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0050  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The [J-magic Campaign](https://attack.mitre.org/campaigns/C0050) was active from mid-2023 to at least mid-2024 and featured the use of the [J-magic](https://attack.mitre.org/software/S1203) backdoor, a custom cd00r variant tailored for use against Juniper routers. The [J-magic Campaign](https://attack.mitre.org/campaigns/C0050) targeted Junos OS routers serving as VPN gateways primarily in the semiconductor, energy, manufacturing, and IT sectors. (Citation: Lumen J-Magic JAN 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0050](https://attack.mitre.org/campaigns/C0050)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
