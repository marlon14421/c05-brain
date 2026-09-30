---
type: "Campaign"
source: MITRE ATT&CK
id: "C0037"
source_url: "https://attack.mitre.org/campaigns/C0037"
created: "2024-07-17"
modified: "2026-07-31"
---
# C0037: Water Curupira Pikabot Distribution

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0037  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[Pikabot](https://attack.mitre.org/software/S1145) was distributed in [Water Curupira Pikabot Distribution](https://attack.mitre.org/campaigns/C0037) throughout 2023 by an entity linked to BlackBasta ransomware deployment via email attachments. This activity followed the take-down of [QakBot](https://attack.mitre.org/software/S0650), with several technical overlaps and similarities with [QakBot](https://attack.mitre.org/software/S0650), indicating a possible connection. The identified activity led to the deployment of tools such as [Cobalt Strike](https://attack.mitre.org/software/S0154), while coinciding with campaigns delivering [DarkGate](https://attack.mitre.org/software/S1111) and [IcedID](https://attack.mitre.org/software/S0483) en route to ransomware deployment.(Citation: TrendMicro Pikabot 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0037](https://attack.mitre.org/campaigns/C0037)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
