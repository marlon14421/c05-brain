---
type: "Campaign"
source: MITRE ATT&CK
id: "C0041"
source_url: "https://attack.mitre.org/campaigns/C0041"
created: "2024-11-20"
modified: "2026-07-31"
---
# C0041: FrostyGoop Incident

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0041  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[FrostyGoop Incident](https://attack.mitre.org/campaigns/C0041) took place in January 2024 against a municipal district heating company in Ukraine. Following initial access via likely exploitation of external facing services, [FrostyGoop](https://attack.mitre.org/software/S1165) was used to manipulate ENCO control systems via legitimate Modbus commands to impact the delivery of heating services to Ukrainian civilians.(Citation: Dragos FROSTYGOOP 2024)(Citation: Nozomi BUSTLEBERM 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0041](https://attack.mitre.org/campaigns/C0041)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
