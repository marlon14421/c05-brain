---
type: "Malware"
source: MITRE ATT&CK
id: "S1180"
source_url: "https://attack.mitre.org/software/S1180"
created: "2024-12-17"
modified: "2024-12-17"
---
# S1180: BlackByte Ransomware

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1180  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[BlackByte Ransomware](https://attack.mitre.org/software/S1180) is uniquely associated with [BlackByte](https://attack.mitre.org/groups/G1043) operations. [BlackByte Ransomware](https://attack.mitre.org/software/S1180) used a common key for infections, allowing for the creation of a universal decryptor.(Citation: Trustwave BlackByte 2021)(Citation: FBI BlackByte 2022) [BlackByte Ransomware](https://attack.mitre.org/software/S1180) was replaced in [BlackByte](https://attack.mitre.org/groups/G1043) operations by [BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) by 2023.(Citation: Microsoft BlackByte 2023)(Citation: Cisco BlackByte 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1180](https://attack.mitre.org/software/S1180)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
