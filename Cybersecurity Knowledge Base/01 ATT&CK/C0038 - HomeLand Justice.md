---
type: "Campaign"
source: MITRE ATT&CK
id: "C0038"
source_url: "https://attack.mitre.org/campaigns/C0038"
created: "2024-08-06"
modified: "2026-07-31"
---
# C0038: HomeLand Justice

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0038  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[HomeLand Justice](https://attack.mitre.org/campaigns/C0038) was a disruptive cyber campaign conducted by Iranian state-affiliated actors against Albanian government networks in July and September 2022. The activity combined ransomware, wiper malware, and data leak operations. Initial access for [HomeLand Justice](https://attack.mitre.org/campaigns/C0038) was established as early as May 2021, and threat actors moved laterally, exfiltrated sensitive information, and maintained persistence for approximately 14 months prior to the destructive phase of the operation. Responsibility was claimed by the "HomeLand Justice" front, which framed the campaign as retaliation against the Mujahedeen-e Khalq (MEK), an Iranian opposition group with a presence in Albania. Multiple Iran-nexus groups are assessed to have participated in the campaign, including [HEXANE](https://attack.mitre.org/groups/G1001) who probed victim infrastructure.(Citation: Mandiant ROADSWEEP August 2022)(Citation: Microsoft Albanian Government Attacks September 2022)(Citation: CISA Iran Albanian Attacks September 2022) A second wave of attacks was launched in September 2022 using similar tactics following public attribution of the previous activity to Iran and the severing of diplomatic ties between Iran and Albania.(Citation: CISA Iran Albanian Attacks September 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0038](https://attack.mitre.org/campaigns/C0038)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
