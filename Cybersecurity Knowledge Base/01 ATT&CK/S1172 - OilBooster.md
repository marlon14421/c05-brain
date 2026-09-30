---
type: "Malware"
source: MITRE ATT&CK
id: "S1172"
source_url: "https://attack.mitre.org/software/S1172"
created: "2024-11-26"
modified: "2024-11-27"
---
# S1172: OilBooster

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1172  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[OilBooster](https://attack.mitre.org/software/S1172) is a downloader written in Microsoft Visual C/C++ that has been used by [OilRig](https://attack.mitre.org/groups/G0049) since at least 2022 including against target organizations in Israel to download and execute files and for exfiltration.(Citation: ESET OilRig Downloaders DEC 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1172](https://attack.mitre.org/software/S1172)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
