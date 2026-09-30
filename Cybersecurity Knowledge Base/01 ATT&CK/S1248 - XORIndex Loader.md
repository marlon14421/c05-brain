---
type: "Malware"
source: MITRE ATT&CK
id: "S1248"
source_url: "https://attack.mitre.org/software/S1248"
created: "2025-10-22"
modified: "2025-10-24"
---
# S1248: XORIndex Loader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1248  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[XORIndex Loader](https://attack.mitre.org/software/S1248) is a XOR-encoded loader that collects host data, decodes follow-on scripts and acts as a downloader for the [BeaverTail](https://attack.mitre.org/software/S1246) malware. [XORIndex Loader](https://attack.mitre.org/software/S1248) was first reported in June 2025. [XORIndex Loader](https://attack.mitre.org/software/S1248) has been leveraged by North Korea-affiliated threat actors identified as [Contagious Interview](https://attack.mitre.org/groups/G1052). [XORIndex Loader](https://attack.mitre.org/software/S1248) has been delivered to victims through code repository sites utilizing typo squatting naming conventions of various npm packages.(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1248](https://attack.mitre.org/software/S1248)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
