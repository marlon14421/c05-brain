---
type: "Malware"
source: MITRE ATT&CK
id: "S1132"
source_url: "https://attack.mitre.org/software/S1132"
created: "2024-05-22"
modified: "2024-08-29"
---
# S1132: IPsec Helper

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1132  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[IPsec Helper](https://attack.mitre.org/software/S1132) is a post-exploitation remote access tool linked to [Agrius](https://attack.mitre.org/groups/G1030) operations. This malware shares significant programming and functional overlaps with [Apostle](https://attack.mitre.org/software/S1133) ransomware, also linked to [Agrius](https://attack.mitre.org/groups/G1030). [IPsec Helper](https://attack.mitre.org/software/S1132) provides basic remote access tool functionality such as uploading files from victim systems, running commands, and deploying additional payloads.(Citation: SentinelOne Agrius 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1132](https://attack.mitre.org/software/S1132)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
