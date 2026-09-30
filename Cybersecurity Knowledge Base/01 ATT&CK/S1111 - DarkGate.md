---
type: "Malware"
source: MITRE ATT&CK
id: "S1111"
source_url: "https://attack.mitre.org/software/S1111"
created: "2024-02-09"
modified: "2026-05-12"
---
# S1111: DarkGate

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1111  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) first emerged in 2018 and has evolved into an initial access and data gathering tool associated with various criminal cyber operations. Written in Delphi and named "DarkGate" by its author, [DarkGate](https://attack.mitre.org/software/S1111) is associated with credential theft, cryptomining, cryptotheft, and pre-ransomware actions.(Citation: Ensilo Darkgate 2018) DarkGate use increased significantly starting in 2022 and is under active development by its author, who provides it as a Malware-as-a-Service offering.(Citation: Trellix Darkgate 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1111](https://attack.mitre.org/software/S1111)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
