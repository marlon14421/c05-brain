---
type: "Campaign"
source: MITRE ATT&CK
id: "C0063"
source_url: "https://attack.mitre.org/campaigns/C0063"
created: "2026-04-22"
modified: "2026-07-31"
---
# C0063: 2025 Poland Wiper Attacks

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0063  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063) is a Russian state-sponsored campaign that conducted destructive cyberattacks against Polish energy infrastructure in December 2025. Targets included more than 30 wind and photovoltaic farms, a combined heat and power (CHP) plant, and a manufacturing sector company. The attacks on the distributed energy resources (DER) disrupted communications between affected facilities and the distribution system operator, but did not impact electricity generation or heat supply. Across the campaign, threat actors deployed two previously undocumented wiper tools, [DynoWiper](https://attack.mitre.org/software/S9038), a Windows-based wiper and [LazyWiper](https://attack.mitre.org/software/S9039), a PowerShell wiper, distributed via malicious Group Policy Objects. At the CHP plant, threat actors had maintained access since at least March 2025, using that foothold to obtain credentials and move laterally before attempting wiper deployment. Some reporting has assessed the activity to be consistent with Russian Federal Security Service (FSB) threat activity group [Dragonfly](https://attack.mitre.org/groups/G0035), also tracked as STATIC TUNDRA, while other reporting attributes the destructive wiper activities to the Russian General Staff Main Intelligence Directorate (GRU) threat activity group ELECTRUM, also tracked as [Sandworm Team](https://attack.mitre.org/groups/G0034).(Citation: CERT Polska)(Citation: Dragos ELECTRUM JAN 2026)(Citation: ESET DynoWiper JAN 2026)(Citation: ESET DynoWiper Update JAN 2026)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0063](https://attack.mitre.org/campaigns/C0063)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
