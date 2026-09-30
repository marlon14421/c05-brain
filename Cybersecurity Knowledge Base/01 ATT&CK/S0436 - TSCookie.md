---
type: "Malware"
source: MITRE ATT&CK
id: "S0436"
source_url: "https://attack.mitre.org/software/S0436"
created: "2020-05-06"
modified: "2025-04-16"
---
# S0436: TSCookie

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0436  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[TSCookie](https://attack.mitre.org/software/S0436) is a remote access tool (RAT) that has been used by [BlackTech](https://attack.mitre.org/groups/G0098) in campaigns against Japanese targets.(Citation: JPCert TSCookie March 2018)(Citation: JPCert BlackTech Malware September 2019). [TSCookie](https://attack.mitre.org/software/S0436) has been referred to as [PLEAD](https://attack.mitre.org/software/S0435) though more recent reporting indicates a separation between the two.(Citation: JPCert PLEAD Downloader June 2018)(Citation: JPCert BlackTech Malware September 2019)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0436](https://attack.mitre.org/software/S0436)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
