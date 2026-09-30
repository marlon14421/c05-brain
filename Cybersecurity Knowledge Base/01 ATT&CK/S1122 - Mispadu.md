---
type: "Malware"
source: MITRE ATT&CK
id: "S1122"
source_url: "https://attack.mitre.org/software/S1122"
created: "2024-03-13"
modified: "2024-04-18"
---
# S1122: Mispadu

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1122  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Mispadu](https://attack.mitre.org/software/S1122) is a banking trojan written in Delphi that was first observed in 2019 and uses a Malware-as-a-Service (MaaS) business model.(Citation: ESET Security Mispadu Facebook Ads 2019)(Citation: SCILabs Malteiro 2021) This malware is operated, managed, and sold by the [Malteiro](https://attack.mitre.org/groups/G1026) cybercriminal group.(Citation: SCILabs Malteiro 2021) [Mispadu](https://attack.mitre.org/software/S1122) has mainly been used to target victims in Brazil and Mexico, and has also had confirmed operations throughout Latin America and Europe.(Citation: SCILabs Malteiro 2021)(Citation: SCILabs URSA/Mispadu Evolution 2023)(Citation: Segurança Informática URSA Sophisticated Loader 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1122](https://attack.mitre.org/software/S1122)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
