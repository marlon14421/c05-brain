---
type: "Malware"
source: MITRE ATT&CK
id: "S1059"
source_url: "https://attack.mitre.org/software/S1059"
created: "2023-01-24"
modified: "2024-04-11"
---
# S1059: metaMain

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1059  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[metaMain](https://attack.mitre.org/software/S1059) is a backdoor used by [Metador](https://attack.mitre.org/groups/G1013) to maintain long-term access to compromised machines; it has also been used to decrypt [Mafalda](https://attack.mitre.org/software/S1060) into memory.(Citation: SentinelLabs Metador Sept 2022)(Citation: SentinelLabs Metador Technical Appendix Sept 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1059](https://attack.mitre.org/software/S1059)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
