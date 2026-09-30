---
type: "Campaign"
source: MITRE ATT&CK
id: "C0059"
source_url: "https://attack.mitre.org/campaigns/C0059"
created: "2025-10-22"
modified: "2026-07-31"
---
# C0059: Salesforce Data Exfiltration

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0059  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The [Salesforce Data Exfiltration](https://attack.mitre.org/campaigns/C0059) campaign began in October 2024 with financially-motivated threat actor UNC6040 using [Spearphishing Voice](https://attack.mitre.org/techniques/T1598/004) (vishing) to compromise corporate Salesforce instances for large-scale data theft and extortion. Following the initial data theft, victim organizations received extortion demands from a separate threat actor, UNC6240, who claimed to be the “ShinyHunters” group. The observed infrastructure and TTPs used during the [Salesforce Data Exfiltration](https://attack.mitre.org/campaigns/C0059) campaign overlap with those used by threat groups with suspected ties to the broader collective known as "The Com.” These overlaps could plausibly be the result of associated actors operating within the same communities and are not necessarily an indication of a direct operational relationship.(Citation: FBI Salesforce Data Theft SEP 2025)(Citation: Google Salesforce JUN 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0059](https://attack.mitre.org/campaigns/C0059)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
