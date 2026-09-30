---
type: "Campaign"
source: MITRE ATT&CK
id: "C0051"
source_url: "https://attack.mitre.org/campaigns/C0051"
created: "2025-02-25"
modified: "2026-07-31"
---
# C0051: APT28 Nearest Neighbor Campaign

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0051  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[APT28 Nearest Neighbor Campaign](https://attack.mitre.org/campaigns/C0051) was conducted by [APT28](https://attack.mitre.org/groups/G0007) from early February 2022 to November 2024 against organizations and individuals with expertise on Ukraine. APT28 primarily leveraged living-off-the-land techniques, while leveraging the zero-day exploitation of CVE-2022-38028. Notably, APT28 leveraged Wi-Fi networks in close proximity to the intended target to gain initial access to the victim environment. By daisy-chaining multiple compromised organizations nearby the intended target, APT28 discovered dual-homed systems (with both a wired and wireless network connection) to enable Wi-Fi and use compromised credentials to connect to the victim network.(Citation: Nearest Neighbor Volexity)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0051](https://attack.mitre.org/campaigns/C0051)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
