---
type: "Malware"
source: MITRE ATT&CK
id: "S1049"
source_url: "https://attack.mitre.org/software/S1049"
created: "2022-10-04"
modified: "2025-10-22"
---
# S1049: SUGARUSH

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1049  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SUGARUSH](https://attack.mitre.org/software/S1049) is a small custom backdoor that can establish a reverse shell over TCP to a hard coded C2 address. [SUGARUSH](https://attack.mitre.org/software/S1049) was first identified during analysis of UNC3890's [C0010](https://attack.mitre.org/campaigns/C0010) campaign targeting Israeli companies, which began in late 2020.(Citation: Mandiant UNC3890 Aug 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1049](https://attack.mitre.org/software/S1049)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
