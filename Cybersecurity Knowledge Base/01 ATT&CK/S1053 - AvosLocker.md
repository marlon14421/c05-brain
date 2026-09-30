---
type: "Malware"
source: MITRE ATT&CK
id: "S1053"
source_url: "https://attack.mitre.org/software/S1053"
created: "2023-01-11"
modified: "2025-04-21"
---
# S1053: AvosLocker

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1053  
**Platforms:** Linux, Windows  
**Tactics:** Not specified

## Source description

[AvosLocker](https://attack.mitre.org/software/S1053) is ransomware written in C++ that has been offered via the Ransomware-as-a-Service (RaaS) model. It was first observed in June 2021 and has been used against financial services, critical manufacturing, government facilities, and other critical infrastructure sectors in the United States. As of March 2022, [AvosLocker](https://attack.mitre.org/software/S1053) had also been used against organizations in Belgium, Canada, China, Germany, Saudi Arabia, Spain, Syria, Taiwan, Turkey, the United Arab Emirates, and the United Kingdom.(Citation: Malwarebytes AvosLocker Jul 2021)(Citation: Trend Micro AvosLocker Apr 2022)(Citation: Joint CSA AvosLocker Mar 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1053](https://attack.mitre.org/software/S1053)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
