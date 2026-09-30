---
type: "Malware"
source: MITRE ATT&CK
id: "S1181"
source_url: "https://attack.mitre.org/software/S1181"
created: "2024-12-17"
modified: "2026-05-12"
---
# S1181: BlackByte 2.0 Ransomware

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1181  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) is a replacement for [BlackByte Ransomware](https://attack.mitre.org/software/S1180). Unlike [BlackByte Ransomware](https://attack.mitre.org/software/S1180), [BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) does not have a common key for victim decryption. [BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) remains uniquely associated with [BlackByte](https://attack.mitre.org/groups/G1043) operations.(Citation: Microsoft BlackByte 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1181](https://attack.mitre.org/software/S1181)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
